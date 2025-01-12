---
author: wanghaisheng
cover:
  alt: cover
  square: https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg
  url: https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg
description: ''
featured: true
keywords: key1, key2, key3
layout: ../../layouts/MarkdownPost.astro
meta:
- content: Daniela Antonova et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-01-12 17:14:21'
tags:
- all search terms
- dataset
theme: light
title: Private Selection with Heterogeneous Sensitivities
---

# title: Private Selection with Heterogeneous Sensitivities 
## publish date: 
**2025-01-09** 
## authors: 
  Daniela Antonova et.al. 
## paper id
2501.05309v1
## download
[2501.05309v1](http://arxiv.org/abs/2501.05309v1)
## abstracts:
Differentially private (DP) selection involves choosing a high-scoring candidate from a finite candidate pool, where each score depends on a sensitive dataset. This problem arises naturally in a variety of contexts including model selection, hypothesis testing, and within many DP algorithms. Classical methods, such as Report Noisy Max (RNM), assume all candidates' scores are equally sensitive to changes in a single individual's data, but this often isn't the case. To address this, algorithms like the Generalised Exponential Mechanism (GEM) leverage variability in candidate sensitivities. However, we observe that while these algorithms can outperform RNM in some situations, they may underperform in others - they can even perform worse than random selection. In this work, we explore how the distribution of scores and sensitivities impacts DP selection mechanisms. In all settings we study, we find that there exists a mechanism that utilises heterogeneity in the candidate sensitivities that outperforms standard mechanisms like RNM. However, no single mechanism uniformly outperforms RNM. We propose using the correlation between the scores and sensitivities as the basis for deciding which DP selection mechanism to use. Further, we design a slight variant of GEM, modified GEM that generally performs well whenever GEM performs poorly. Relying on the correlation heuristic we propose combined GEM, which adaptively chooses between GEM and modified GEM and outperforms both in polarised settings.
## QA:
coming soon
