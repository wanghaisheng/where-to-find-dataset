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
- content: Jing Li et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-31 11:40:25'
tags:
- all search terms
- dataset
theme: light
title: Learnable cut flow
---

# title: Learnable cut flow 
## publish date: 
**2025-03-28** 
## authors: 
  Jing Li et.al. 
## paper id
2503.22498v1
## download
[2503.22498v1](http://arxiv.org/abs/2503.22498v1)
## abstracts:
Neural networks have emerged as a powerful paradigm for tasks in high energy physics, yet their opaque training process renders them as a black box. In contrast, the traditional cut flow method offers simplicity and interpretability but demands human effort to identify optimal boundaries. To merge the strengths of both approaches, we propose the Learnable Cut Flow (LCF), a neural network that transforms the traditional cut selection into a fully differentiable, data-driven process. LCF implements two cut strategies-parallel, where observable distributions are treated independently, and sequential, where prior cuts shape subsequent ones-to flexibly determine optimal boundaries. Building on this, we introduce the Learnable Importance, a metric that quantifies feature importance and adjusts their contributions to the loss accordingly, offering model-driven insights unlike ad-hoc metrics. To ensure differentiability, a modified loss function replaces hard cuts with mask operations, preserving data shape throughout the training process. LCF is tested on six varied mock datasets and a realistic diboson vs. QCD dataset. Results demonstrate that LCF (1) accurately learns cut boundaries across typical feature distributions in both parallel and sequential strategies, (2) assigns higher importance to discriminative features with minimal overlap, (3) handles redundant or correlated features robustly, and (4) performs effectively in real-world scenarios. In diboson dataset, LCF initially underperforms boosted decision trees and multiplayer perceptrons when using all observables. However, pruning less critical features-guided by learned importance-boosts its performance to match or exceed these baselines. LCF bridges the gap between traditional cut flow method and modern black-box neural networks, delivering actionable insights into the training process and feature importance.
## QA:
coming soon
