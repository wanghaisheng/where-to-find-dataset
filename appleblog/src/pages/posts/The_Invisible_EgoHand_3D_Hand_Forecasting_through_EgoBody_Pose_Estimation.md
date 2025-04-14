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
- content: Masashi Hatano et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-04-14 11:41:14'
tags:
- dataset
- all search terms
theme: light
title: The Invisible EgoHand 3D Hand Forecasting through EgoBody Pose Estimation
---

# title: The Invisible EgoHand 3D Hand Forecasting through EgoBody Pose Estimation 
## publish date: 
**2025-04-11** 
## authors: 
  Masashi Hatano et.al. 
## paper id
2504.08654v1
## download
[2504.08654v1](http://arxiv.org/abs/2504.08654v1)
## abstracts:
Forecasting hand motion and pose from an egocentric perspective is essential for understanding human intention. However, existing methods focus solely on predicting positions without considering articulation, and only when the hands are visible in the field of view. This limitation overlooks the fact that approximate hand positions can still be inferred even when they are outside the camera's view. In this paper, we propose a method to forecast the 3D trajectories and poses of both hands from an egocentric video, both in and out of the field of view. We propose a diffusion-based transformer architecture for Egocentric Hand Forecasting, EgoH4, which takes as input the observation sequence and camera poses, then predicts future 3D motion and poses for both hands of the camera wearer. We leverage full-body pose information, allowing other joints to provide constraints on hand motion. We denoise the hand and body joints along with a visibility predictor for hand joints and a 3D-to-2D reprojection loss that minimizes the error when hands are in-view. We evaluate EgoH4 on the Ego-Exo4D dataset, combining subsets with body and hand annotations. We train on 156K sequences and evaluate on 34K sequences, respectively. EgoH4 improves the performance by 3.4cm and 5.1cm over the baseline in terms of ADE for hand trajectory forecasting and MPJPE for hand pose forecasting. Project page: https://masashi-hatano.github.io/EgoH4/
## QA:
coming soon
