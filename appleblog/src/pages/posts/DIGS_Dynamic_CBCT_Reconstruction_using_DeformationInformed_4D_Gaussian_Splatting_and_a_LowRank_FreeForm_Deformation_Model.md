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
- content: Yuliang Huang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-30 11:47:23'
tags:
- all search terms
- dataset
theme: light
title: DIGS Dynamic CBCT Reconstruction using DeformationInformed 4D Gaussian Splatting
  and a LowRank FreeForm Deformation Model
---

# title: DIGS Dynamic CBCT Reconstruction using DeformationInformed 4D Gaussian Splatting and a LowRank FreeForm Deformation Model 
## publish date: 
**2025-06-27** 
## authors: 
  Yuliang Huang et.al. 
## paper id
2506.22280v1
## download
[2506.22280v1](http://arxiv.org/abs/2506.22280v1)
## abstracts:
3D Cone-Beam CT (CBCT) is widely used in radiotherapy but suffers from motion artifacts due to breathing. A common clinical approach mitigates this by sorting projections into respiratory phases and reconstructing images per phase, but this does not account for breathing variability. Dynamic CBCT instead reconstructs images at each projection, capturing continuous motion without phase sorting. Recent advancements in 4D Gaussian Splatting (4DGS) offer powerful tools for modeling dynamic scenes, yet their application to dynamic CBCT remains underexplored. Existing 4DGS methods, such as HexPlane, use implicit motion representations, which are computationally expensive. While explicit low-rank motion models have been proposed, they lack spatial regularization, leading to inconsistencies in Gaussian motion. To address these limitations, we introduce a free-form deformation (FFD)-based spatial basis function and a deformation-informed framework that enforces consistency by coupling the temporal evolution of Gaussian's mean position, scale, and rotation under a unified deformation field. We evaluate our approach on six CBCT datasets, demonstrating superior image quality with a 6x speedup over HexPlane. These results highlight the potential of deformation-informed 4DGS for efficient, motion-compensated CBCT reconstruction. The code is available at https://github.com/Yuliang-Huang/DIGS.
## QA:
coming soon
