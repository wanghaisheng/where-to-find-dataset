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
- content: Yue Chen et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-15 14:51:07'
tags:
- all search terms
- dataset
theme: light
title: Feat2GS Probing Visual Foundation Models with Gaussian Splatting
---

# title: Feat2GS Probing Visual Foundation Models with Gaussian Splatting 
## publish date: 
**2024-12-12** 
## authors: 
  Yue Chen et.al. 
## paper id
2412.09606v1
## download
[2412.09606v1](http://arxiv.org/abs/2412.09606v1)
## abstracts:
Given that visual foundation models (VFMs) are trained on extensive datasets but often limited to 2D images, a natural question arises: how well do they understand the 3D world? With the differences in architecture and training protocols (i.e., objectives, proxy tasks), a unified framework to fairly and comprehensively probe their 3D awareness is urgently needed. Existing works on 3D probing suggest single-view 2.5D estimation (e.g., depth and normal) or two-view sparse 2D correspondence (e.g., matching and tracking). Unfortunately, these tasks ignore texture awareness, and require 3D data as ground-truth, which limits the scale and diversity of their evaluation set. To address these issues, we introduce Feat2GS, which readout 3D Gaussians attributes from VFM features extracted from unposed images. This allows us to probe 3D awareness for geometry and texture via novel view synthesis, without requiring 3D data. Additionally, the disentanglement of 3DGS parameters - geometry ($\boldsymbol{x}, \alpha, \Sigma$) and texture ($\boldsymbol{c}$) - enables separate analysis of texture and geometry awareness. Under Feat2GS, we conduct extensive experiments to probe the 3D awareness of several VFMs, and investigate the ingredients that lead to a 3D aware VFM. Building on these findings, we develop several variants that achieve state-of-the-art across diverse datasets. This makes Feat2GS useful for probing VFMs, and as a simple-yet-effective baseline for novel-view synthesis. Code and data will be made available at https://fanegg.github.io/Feat2GS/.
## QA:
coming soon
