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
- content: Diego Adame et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-12 11:43:51'
tags:
- dataset
- all search terms
theme: light
title: TopoVMUNetV2 Encoding Topology into Vision Mamba UNet for Polyp Segmentation
---

# title: TopoVMUNetV2 Encoding Topology into Vision Mamba UNet for Polyp Segmentation 
## publish date: 
**2025-05-09** 
## authors: 
  Diego Adame et.al. 
## paper id
2505.06210v1
## download
[2505.06210v1](http://arxiv.org/abs/2505.06210v1)
## abstracts:
Convolutional neural network (CNN) and Transformer-based architectures are two dominant deep learning models for polyp segmentation. However, CNNs have limited capability for modeling long-range dependencies, while Transformers incur quadratic computational complexity. Recently, State Space Models such as Mamba have been recognized as a promising approach for polyp segmentation because they not only model long-range interactions effectively but also maintain linear computational complexity. However, Mamba-based architectures still struggle to capture topological features (e.g., connected components, loops, voids), leading to inaccurate boundary delineation and polyp segmentation. To address these limitations, we propose a new approach called Topo-VM-UNetV2, which encodes topological features into the Mamba-based state-of-the-art polyp segmentation model, VM-UNetV2. Our method consists of two stages: Stage 1: VM-UNetV2 is used to generate probability maps (PMs) for the training and test images, which are then used to compute topology attention maps. Specifically, we first compute persistence diagrams of the PMs, then we generate persistence score maps by assigning persistence values (i.e., the difference between death and birth times) of each topological feature to its birth location, finally we transform persistence scores into attention weights using the sigmoid function. Stage 2: These topology attention maps are integrated into the semantics and detail infusion (SDI) module of VM-UNetV2 to form a topology-guided semantics and detail infusion (Topo-SDI) module for enhancing the segmentation results. Extensive experiments on five public polyp segmentation datasets demonstrate the effectiveness of our proposed method. The code will be made publicly available.
## QA:
coming soon
