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
- content: Justin Kerr et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-30 11:37:54'
tags:
- all search terms
- dataset
theme: light
title: Robot See Robot Do Imitating Articulated Object Manipulation with Monocular
  4D Reconstruction
---

# title: Robot See Robot Do Imitating Articulated Object Manipulation with Monocular 4D Reconstruction 
## publish date: 
**2024-09-26** 
## authors: 
  Justin Kerr et.al. 
## paper id
2409.18121v1
## download
[2409.18121v1](http://arxiv.org/abs/2409.18121v1)
## abstracts:
Humans can learn to manipulate new objects by simply watching others; providing robots with the ability to learn from such demonstrations would enable a natural interface specifying new behaviors. This work develops Robot See Robot Do (RSRD), a method for imitating articulated object manipulation from a single monocular RGB human demonstration given a single static multi-view object scan. We first propose 4D Differentiable Part Models (4D-DPM), a method for recovering 3D part motion from a monocular video with differentiable rendering. This analysis-by-synthesis approach uses part-centric feature fields in an iterative optimization which enables the use of geometric regularizers to recover 3D motions from only a single video. Given this 4D reconstruction, the robot replicates object trajectories by planning bimanual arm motions that induce the demonstrated object part motion. By representing demonstrations as part-centric trajectories, RSRD focuses on replicating the demonstration's intended behavior while considering the robot's own morphological limits, rather than attempting to reproduce the hand's motion. We evaluate 4D-DPM's 3D tracking accuracy on ground truth annotated 3D part trajectories and RSRD's physical execution performance on 9 objects across 10 trials each on a bimanual YuMi robot. Each phase of RSRD achieves an average of 87% success rate, for a total end-to-end success rate of 60% across 90 trials. Notably, this is accomplished using only feature fields distilled from large pretrained vision models -- without any task-specific training, fine-tuning, dataset collection, or annotation. Project page: https://robot-see-robot-do.github.io
## QA:
coming soon
