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
- content: David Serrano-Lozano et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-02 11:40:46'
tags:
- all search terms
- dataset
theme: light
title: Adaptive Blind AllinOne Image Restoration
---

# title: Adaptive Blind AllinOne Image Restoration 
## publish date: 
**2024-11-27** 
## authors: 
  David Serrano-Lozano et.al. 
## paper id
2411.18412v1
## download
[2411.18412v1](http://arxiv.org/abs/2411.18412v1)
## abstracts:
Blind all-in-one image restoration models aim to recover a high-quality image from an input degraded with unknown distortions. However, these models require all the possible degradation types to be defined during the training stage while showing limited generalization to unseen degradations, which limits their practical application in complex cases. In this paper, we propose a simple but effective adaptive blind all-in-one restoration (ABAIR) model, which can address multiple degradations, generalizes well to unseen degradations, and efficiently incorporate new degradations by training a small fraction of parameters. First, we train our baseline model on a large dataset of natural images with multiple synthetic degradations, augmented with a segmentation head to estimate per-pixel degradation types, resulting in a powerful backbone able to generalize to a wide range of degradations. Second, we adapt our baseline model to varying image restoration tasks using independent low-rank adapters. Third, we learn to adaptively combine adapters to versatile images via a flexible and lightweight degradation estimator. Our model is both powerful in handling specific distortions and flexible in adapting to complex tasks, it not only outperforms the state-of-the-art by a large margin on five- and three-task IR setups, but also shows improved generalization to unseen degradations and also composite distortions.
## QA:
coming soon
