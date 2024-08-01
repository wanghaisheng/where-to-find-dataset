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
- content: Jianxin Huang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-02 01:35:21'
tags:
- all search terms
- dataset
theme: light
title: RoadFormer Delivering RGBX Scene Parsing through ScaleAware Information Decoupling
  and Advanced Heterogeneous Feature Fusion
---

# title: RoadFormer Delivering RGBX Scene Parsing through ScaleAware Information Decoupling and Advanced Heterogeneous Feature Fusion 
## publish date: 
**2024-07-31** 
## authors: 
  Jianxin Huang et.al. 
## paper id
2407.21631v1
## download
[2407.21631v1](http://arxiv.org/abs/2407.21631v1)
## abstracts:
Task-specific data-fusion networks have marked considerable achievements in urban scene parsing. Among these networks, our recently proposed RoadFormer successfully extracts heterogeneous features from RGB images and surface normal maps and fuses these features through attention mechanisms, demonstrating compelling efficacy in RGB-Normal road scene parsing. However, its performance significantly deteriorates when handling other types/sources of data or performing more universal, all-category scene parsing tasks. To overcome these limitations, this study introduces RoadFormer+, an efficient, robust, and adaptable model capable of effectively fusing RGB-X data, where ``X'', represents additional types/modalities of data such as depth, thermal, surface normal, and polarization. Specifically, we propose a novel hybrid feature decoupling encoder to extract heterogeneous features and decouple them into global and local components. These decoupled features are then fused through a dual-branch multi-scale heterogeneous feature fusion block, which employs parallel Transformer attentions and convolutional neural network modules to merge multi-scale features across different scales and receptive fields. The fused features are subsequently fed into a decoder to generate the final semantic predictions. Notably, our proposed RoadFormer+ ranks first on the KITTI Road benchmark and achieves state-of-the-art performance in mean intersection over union on the Cityscapes, MFNet, FMB, and ZJU datasets. Moreover, it reduces the number of learnable parameters by 65\% compared to RoadFormer. Our source code will be publicly available at mias.group/RoadFormerPlus.
## QA:
coming soon
