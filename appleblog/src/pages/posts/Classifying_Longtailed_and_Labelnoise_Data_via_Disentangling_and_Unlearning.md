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
- content: Chen Shu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-17 11:38:50'
tags:
- dataset
- all search terms
theme: light
title: Classifying Longtailed and Labelnoise Data via Disentangling and Unlearning
---

# title: Classifying Longtailed and Labelnoise Data via Disentangling and Unlearning 
## publish date: 
**2025-03-14** 
## authors: 
  Chen Shu et.al. 
## paper id
2503.11414v1
## download
[2503.11414v1](http://arxiv.org/abs/2503.11414v1)
## abstracts:
In real-world datasets, the challenges of long-tailed distributions and noisy labels often coexist, posing obstacles to the model training and performance. Existing studies on long-tailed noisy label learning (LTNLL) typically assume that the generation of noisy labels is independent of the long-tailed distribution, which may not be true from a practical perspective. In real-world situaiton, we observe that the tail class samples are more likely to be mislabeled as head, exacerbating the original degree of imbalance. We call this phenomenon as ``tail-to-head (T2H)'' noise. T2H noise severely degrades model performance by polluting the head classes and forcing the model to learn the tail samples as head. To address this challenge, we investigate the dynamic misleading process of the nosiy labels and propose a novel method called Disentangling and Unlearning for Long-tailed and Label-noisy data (DULL). It first employs the Inner-Feature Disentangling (IFD) to disentangle feature internally. Based on this, the Inner-Feature Partial Unlearning (IFPU) is then applied to weaken and unlearn incorrect feature regions correlated to wrong classes. This method prevents the model from being misled by noisy labels, enhancing the model's robustness against noise. To provide a controlled experimental environment, we further propose a new noise addition algorithm to simulate T2H noise. Extensive experiments on both simulated and real-world datasets demonstrate the effectiveness of our proposed method.
## QA:
coming soon
