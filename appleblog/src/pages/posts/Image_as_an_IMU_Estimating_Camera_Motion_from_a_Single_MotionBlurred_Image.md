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
- content: Jerred Chen et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-24 11:39:26'
tags:
- dataset
- all search terms
theme: light
title: Image as an IMU Estimating Camera Motion from a Single MotionBlurred Image
---

# title: Image as an IMU Estimating Camera Motion from a Single MotionBlurred Image 
## publish date: 
**2025-03-21** 
## authors: 
  Jerred Chen et.al. 
## paper id
2503.17358v1
## download
[2503.17358v1](http://arxiv.org/abs/2503.17358v1)
## abstracts:
In many robotics and VR/AR applications, fast camera motions cause a high level of motion blur, causing existing camera pose estimation methods to fail. In this work, we propose a novel framework that leverages motion blur as a rich cue for motion estimation rather than treating it as an unwanted artifact. Our approach works by predicting a dense motion flow field and a monocular depth map directly from a single motion-blurred image. We then recover the instantaneous camera velocity by solving a linear least squares problem under the small motion assumption. In essence, our method produces an IMU-like measurement that robustly captures fast and aggressive camera movements. To train our model, we construct a large-scale dataset with realistic synthetic motion blur derived from ScanNet++v2 and further refine our model by training end-to-end on real data using our fully differentiable pipeline. Extensive evaluations on real-world benchmarks demonstrate that our method achieves state-of-the-art angular and translational velocity estimates, outperforming current methods like MASt3R and COLMAP.
## QA:
coming soon
