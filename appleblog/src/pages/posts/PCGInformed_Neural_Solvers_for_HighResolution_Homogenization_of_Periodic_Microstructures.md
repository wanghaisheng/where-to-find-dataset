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
- content: Yu Xing et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-23 11:47:46'
tags:
- all search terms
- dataset
theme: light
title: PCGInformed Neural Solvers for HighResolution Homogenization of Periodic Microstructures
---

# title: PCGInformed Neural Solvers for HighResolution Homogenization of Periodic Microstructures 
## publish date: 
**2025-06-20** 
## authors: 
  Yu Xing et.al. 
## paper id
2506.17087v1
## download
[2506.17087v1](http://arxiv.org/abs/2506.17087v1)
## abstracts:
The mechanical properties of periodic microstructures are pivotal in various engineering applications. Homogenization theory is a powerful tool for predicting these properties by averaging the behavior of complex microstructures over a representative volume element. However, traditional numerical solvers for homogenization problems can be computationally expensive, especially for high-resolution and complicated topology and geometry. Existing learning-based methods, while promising, often struggle with accuracy and generalization in such scenarios. To address these challenges, we present CGINS, a preconditioned-conjugate-gradient-solver-informed neural network for solving homogenization problems. CGINS leverages sparse and periodic 3D convolution to enable high-resolution learning while ensuring structural periodicity. It features a multi-level network architecture that facilitates effective learning across different scales and employs minimum potential energy as label-free loss functions for self-supervised learning. The integrated preconditioned conjugate gradient iterations ensure that the network provides PCG-friendly initial solutions for fast convergence and high accuracy. Additionally, CGINS imposes a global displacement constraint to ensure physical consistency, addressing a key limitation in prior methods that rely on Dirichlet anchors. Evaluated on large-scale datasets with diverse topologies and material configurations, CGINS achieves state-of-the-art accuracy (relative error below 1%) and outperforms both learning-based baselines and GPU-accelerated numerical solvers. Notably, it delivers 2 times to 10 times speedups over traditional methods while maintaining physically reliable predictions at resolutions up to $512^3$.
## QA:
coming soon
