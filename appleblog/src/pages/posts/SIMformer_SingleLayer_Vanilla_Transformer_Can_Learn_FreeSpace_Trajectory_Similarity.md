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
- content: Chuang Yang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-21 11:37:23'
tags:
- all search terms
- dataset
theme: light
title: SIMformer SingleLayer Vanilla Transformer Can Learn FreeSpace Trajectory Similarity
---

# title: SIMformer SingleLayer Vanilla Transformer Can Learn FreeSpace Trajectory Similarity 
## publish date: 
**2024-10-18** 
## authors: 
  Chuang Yang et.al. 
## paper id
2410.14629v1
## download
[2410.14629v1](http://arxiv.org/abs/2410.14629v1)
## abstracts:
Free-space trajectory similarity calculation, e.g., DTW, Hausdorff, and Frechet, often incur quadratic time complexity, thus learning-based methods have been proposed to accelerate the computation. The core idea is to train an encoder to transform trajectories into representation vectors and then compute vector similarity to approximate the ground truth. However, existing methods face dual challenges of effectiveness and efficiency: 1) they all utilize Euclidean distance to compute representation similarity, which leads to the severe curse of dimensionality issue -- reducing the distinguishability among representations and significantly affecting the accuracy of subsequent similarity search tasks; 2) most of them are trained in triplets manner and often necessitate additional information which downgrades the efficiency; 3) previous studies, while emphasizing the scalability in terms of efficiency, overlooked the deterioration of effectiveness when the dataset size grows. To cope with these issues, we propose a simple, yet accurate, fast, scalable model that only uses a single-layer vanilla transformer encoder as the feature extractor and employs tailored representation similarity functions to approximate various ground truth similarity measures. Extensive experiments demonstrate our model significantly mitigates the curse of dimensionality issue and outperforms the state-of-the-arts in effectiveness, efficiency, and scalability.
## QA:
coming soon
