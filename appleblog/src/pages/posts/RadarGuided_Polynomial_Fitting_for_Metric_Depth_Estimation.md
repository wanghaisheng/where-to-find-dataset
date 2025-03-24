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
- content: Patrick Rim et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-24 11:39:34'
tags:
- dataset
- all search terms
theme: light
title: RadarGuided Polynomial Fitting for Metric Depth Estimation
---

# title: RadarGuided Polynomial Fitting for Metric Depth Estimation 
## publish date: 
**2025-03-21** 
## authors: 
  Patrick Rim et.al. 
## paper id
2503.17182v1
## download
[2503.17182v1](http://arxiv.org/abs/2503.17182v1)
## abstracts:
We propose PolyRad, a novel radar-guided depth estimation method that introduces polynomial fitting to transform scaleless depth predictions from pretrained monocular depth estimation (MDE) models into metric depth maps. Unlike existing approaches that rely on complex architectures or expensive sensors, our method is grounded in a simple yet fundamental insight: using polynomial coefficients predicted from cheap, ubiquitous radar data to adaptively adjust depth predictions non-uniformly across depth ranges. Although MDE models often infer reasonably accurate local depth structure within each object or local region, they may misalign these regions relative to one another, making a linear scale-and-shift transformation insufficient given three or more of these regions. In contrast, PolyRad generalizes beyond linear transformations and is able to correct such misalignments by introducing inflection points. Importantly, our polynomial fitting framework preserves structural consistency through a novel training objective that enforces monotonicity via first-derivative regularization. PolyRad achieves state-of-the-art performance on the nuScenes, ZJU-4DRadarCam, and View-of-Delft datasets, outperforming existing methods by 30.3% in MAE and 37.2% in RMSE.
## QA:
coming soon
