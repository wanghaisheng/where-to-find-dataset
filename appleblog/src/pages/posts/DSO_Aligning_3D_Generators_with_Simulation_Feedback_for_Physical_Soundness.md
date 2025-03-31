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
- content: Ruining Li et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-31 11:40:18'
tags:
- all search terms
- dataset
theme: light
title: DSO Aligning 3D Generators with Simulation Feedback for Physical Soundness
---

# title: DSO Aligning 3D Generators with Simulation Feedback for Physical Soundness 
## publish date: 
**2025-03-28** 
## authors: 
  Ruining Li et.al. 
## paper id
2503.22677v1
## download
[2503.22677v1](http://arxiv.org/abs/2503.22677v1)
## abstracts:
Most 3D object generators focus on aesthetic quality, often neglecting physical constraints necessary in applications. One such constraint is that the 3D object should be self-supporting, i.e., remains balanced under gravity. Prior approaches to generating stable 3D objects used differentiable physics simulators to optimize geometry at test-time, which is slow, unstable, and prone to local optima. Inspired by the literature on aligning generative models to external feedback, we propose Direct Simulation Optimization (DSO), a framework to use the feedback from a (non-differentiable) simulator to increase the likelihood that the 3D generator outputs stable 3D objects directly. We construct a dataset of 3D objects labeled with a stability score obtained from the physics simulator. We can then fine-tune the 3D generator using the stability score as the alignment metric, via direct preference optimization (DPO) or direct reward optimization (DRO), a novel objective, which we introduce, to align diffusion models without requiring pairwise preferences. Our experiments show that the fine-tuned feed-forward generator, using either DPO or DRO objective, is much faster and more likely to produce stable objects than test-time optimization. Notably, the DSO framework works even without any ground-truth 3D objects for training, allowing the 3D generator to self-improve by automatically collecting simulation feedback on its own outputs.
## QA:
coming soon
