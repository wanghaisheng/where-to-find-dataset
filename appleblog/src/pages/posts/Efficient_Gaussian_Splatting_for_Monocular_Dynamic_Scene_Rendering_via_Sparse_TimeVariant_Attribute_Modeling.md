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
- content: Hanyang Kong et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-03 11:38:10'
tags:
- dataset
- all search terms
theme: light
title: Efficient Gaussian Splatting for Monocular Dynamic Scene Rendering via Sparse
  TimeVariant Attribute Modeling
---

# title: Efficient Gaussian Splatting for Monocular Dynamic Scene Rendering via Sparse TimeVariant Attribute Modeling 
## publish date: 
**2025-02-27** 
## authors: 
  Hanyang Kong et.al. 
## paper id
2502.20378v1
## download
[2502.20378v1](http://arxiv.org/abs/2502.20378v1)
## abstracts:
Rendering dynamic scenes from monocular videos is a crucial yet challenging task. The recent deformable Gaussian Splatting has emerged as a robust solution to represent real-world dynamic scenes. However, it often leads to heavily redundant Gaussians, attempting to fit every training view at various time steps, leading to slower rendering speeds. Additionally, the attributes of Gaussians in static areas are time-invariant, making it unnecessary to model every Gaussian, which can cause jittering in static regions. In practice, the primary bottleneck in rendering speed for dynamic scenes is the number of Gaussians. In response, we introduce Efficient Dynamic Gaussian Splatting (EDGS), which represents dynamic scenes via sparse time-variant attribute modeling. Our approach formulates dynamic scenes using a sparse anchor-grid representation, with the motion flow of dense Gaussians calculated via a classical kernel representation. Furthermore, we propose an unsupervised strategy to efficiently filter out anchors corresponding to static areas. Only anchors associated with deformable objects are input into MLPs to query time-variant attributes. Experiments on two real-world datasets demonstrate that our EDGS significantly improves the rendering speed with superior rendering quality compared to previous state-of-the-art methods.
## QA:
coming soon
