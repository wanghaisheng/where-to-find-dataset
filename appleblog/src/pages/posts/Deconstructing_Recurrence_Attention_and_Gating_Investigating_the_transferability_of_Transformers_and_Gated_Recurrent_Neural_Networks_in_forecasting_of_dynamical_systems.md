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
- content: Hunter S. Heidenreich et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-07 11:36:42'
tags:
- dataset
- all search terms
theme: light
title: Deconstructing Recurrence Attention and Gating Investigating the transferability
  of Transformers and Gated Recurrent Neural Networks in forecasting of dynamical
  systems
---

# title: Deconstructing Recurrence Attention and Gating Investigating the transferability of Transformers and Gated Recurrent Neural Networks in forecasting of dynamical systems 
## publish date: 
**2024-10-03** 
## authors: 
  Hunter S. Heidenreich et.al. 
## paper id
2410.02654v1
## download
[2410.02654v1](http://arxiv.org/abs/2410.02654v1)
## abstracts:
Machine learning architectures, including transformers and recurrent neural networks (RNNs) have revolutionized forecasting in applications ranging from text processing to extreme weather. Notably, advanced network architectures, tuned for applications such as natural language processing, are transferable to other tasks such as spatiotemporal forecasting tasks. However, there is a scarcity of ablation studies to illustrate the key components that enable this forecasting accuracy. The absence of such studies, although explainable due to the associated computational cost, intensifies the belief that these models ought to be considered as black boxes. In this work, we decompose the key architectural components of the most powerful neural architectures, namely gating and recurrence in RNNs, and attention mechanisms in transformers. Then, we synthesize and build novel hybrid architectures from the standard blocks, performing ablation studies to identify which mechanisms are effective for each task. The importance of considering these components as hyper-parameters that can augment the standard architectures is exhibited on various forecasting datasets, from the spatiotemporal chaotic dynamics of the multiscale Lorenz 96 system, the Kuramoto-Sivashinsky equation, as well as standard real world time-series benchmarks. A key finding is that neural gating and attention improves the performance of all standard RNNs in most tasks, while the addition of a notion of recurrence in transformers is detrimental. Furthermore, our study reveals that a novel, sparsely used, architecture which integrates Recurrent Highway Networks with neural gating and attention mechanisms, emerges as the best performing architecture in high-dimensional spatiotemporal forecasting of dynamical systems.
## QA:
coming soon
