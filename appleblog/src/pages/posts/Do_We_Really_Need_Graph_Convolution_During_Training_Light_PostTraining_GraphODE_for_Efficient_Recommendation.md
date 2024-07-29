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
- content: Weizhi Zhang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-29 11:32:40'
tags:
- dataset on github
- all search terms
theme: light
title: Do We Really Need Graph Convolution During Training Light PostTraining GraphODE
  for Efficient Recommendation
---

# title: Do We Really Need Graph Convolution During Training Light PostTraining GraphODE for Efficient Recommendation 
## publish date: 
**2024-07-26** 
## authors: 
  Weizhi Zhang et.al. 
## paper id
2407.18910v1
## download
[2407.18910v1](http://arxiv.org/abs/2407.18910v1)
## abstracts:
The efficiency and scalability of graph convolution networks (GCNs) in training recommender systems (RecSys) have been persistent concerns, hindering their deployment in real-world applications. This paper presents a critical examination of the necessity of graph convolutions during the training phase and introduces an innovative alternative: the Light Post-Training Graph Ordinary-Differential-Equation (LightGODE). Our investigation reveals that the benefits of GCNs are more pronounced during testing rather than training. Motivated by this, LightGODE utilizes a novel post-training graph convolution method that bypasses the computation-intensive message passing of GCNs and employs a non-parametric continuous graph ordinary-differential-equation (ODE) to dynamically model node representations. This approach drastically reduces training time while achieving fine-grained post-training graph convolution to avoid the distortion of the original training embedding space, termed the embedding discrepancy issue. We validate our model across several real-world datasets of different scales, demonstrating that LightGODE not only outperforms GCN-based models in terms of efficiency and effectiveness but also significantly mitigates the embedding discrepancy commonly associated with deeper graph convolution layers. Our LightGODE challenges the prevailing paradigms in RecSys training and suggests re-evaluating the role of graph convolutions, potentially guiding future developments of efficient large-scale graph-based RecSys.
## QA:
coming soon
