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
- content: Liangze Jiang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-07 11:36:36'
tags:
- dataset
- all search terms
theme: light
title: OODChameleon Is Algorithm Selection for OOD Generalization Learnable
---

# title: OODChameleon Is Algorithm Selection for OOD Generalization Learnable 
## publish date: 
**2024-10-03** 
## authors: 
  Liangze Jiang et.al. 
## paper id
2410.02735v1
## download
[2410.02735v1](http://arxiv.org/abs/2410.02735v1)
## abstracts:
Out-of-distribution (OOD) generalization is challenging because distribution shifts come in many forms. A multitude of learning algorithms exist and each can improve performance in specific OOD situations. We posit that much of the challenge of OOD generalization lies in choosing the right algorithm for the right dataset. However, such algorithm selection is often elusive under complex real-world shifts. In this work, we formalize the task of algorithm selection for OOD generalization and investigate whether it could be approached by learning. We propose a solution, dubbed OOD-Chameleon that treats the task as a supervised classification over candidate algorithms. We construct a dataset of datasets to learn from, which represents diverse types, magnitudes and combinations of shifts (covariate shift, label shift, spurious correlations). We train the model to predict the relative performance of algorithms given a dataset's characteristics. This enables a priori selection of the best learning strategy, i.e. without training various models as needed with traditional model selection. Our experiments show that the adaptive selection outperforms any individual algorithm and simple selection heuristics, on unseen datasets of controllable and realistic image data. Inspecting the model shows that it learns non-trivial data/algorithms interactions, and reveals the conditions for any one algorithm to surpass another. This opens new avenues for (1) enhancing OOD generalization with existing algorithms instead of designing new ones, and (2) gaining insights into the applicability of existing algorithms with respect to datasets' properties.
## QA:
coming soon
