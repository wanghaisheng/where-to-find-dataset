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
- content: Mingyuan Meng et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-30 11:35:40'
tags:
- all search terms
- dataset
theme: light
title: Advancing Deformable Medical Image Registration with Multiaxis Crosscovariance
  Attention
---

# title: Advancing Deformable Medical Image Registration with Multiaxis Crosscovariance Attention 
## publish date: 
**2024-12-24** 
## authors: 
  Mingyuan Meng et.al. 
## paper id
2412.18545v1
## download
[2412.18545v1](http://arxiv.org/abs/2412.18545v1)
## abstracts:
Deformable image registration is a fundamental requirement for medical image analysis. Recently, transformers have been widely used in deep learning-based registration methods for their ability to capture long-range dependency via self-attention (SA). However, the high computation and memory loads of SA (growing quadratically with the spatial resolution) hinder transformers from processing subtle textural information in high-resolution image features, e.g., at the full and half image resolutions. This limits deformable registration as the high-resolution textural information is crucial for finding precise pixel-wise correspondence between subtle anatomical structures. Cross-covariance Attention (XCA), as a "transposed" version of SA that operates across feature channels, has complexity growing linearly with the spatial resolution, providing the feasibility of capturing long-range dependency among high-resolution image features. However, existing XCA-based transformers merely capture coarse global long-range dependency, which are unsuitable for deformable image registration relying primarily on fine-grained local correspondence. In this study, we propose to improve existing deep learning-based registration methods by embedding a new XCA mechanism. To this end, we design an XCA-based transformer block optimized for deformable medical image registration, named Multi-Axis XCA (MAXCA). Our MAXCA serves as a general network block that can be embedded into various registration network architectures. It can capture both global and local long-range dependency among high-resolution image features by applying regional and dilated XCA in parallel via a multi-axis design. Extensive experiments on two well-benchmarked inter-/intra-patient registration tasks with seven public medical datasets demonstrate that our MAXCA block enables state-of-the-art registration performance.
## QA:
coming soon
