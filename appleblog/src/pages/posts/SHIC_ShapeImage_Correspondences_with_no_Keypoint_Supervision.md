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
- content: Aleksandar Shtedritski et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-29 11:32:40'
tags:
- dataset on github
- all search terms
theme: light
title: SHIC ShapeImage Correspondences with no Keypoint Supervision
---

# title: SHIC ShapeImage Correspondences with no Keypoint Supervision 
## publish date: 
**2024-07-26** 
## authors: 
  Aleksandar Shtedritski et.al. 
## paper id
2407.18907v1
## download
[2407.18907v1](http://arxiv.org/abs/2407.18907v1)
## abstracts:
Canonical surface mapping generalizes keypoint detection by assigning each pixel of an object to a corresponding point in a 3D template. Popularised by DensePose for the analysis of humans, authors have since attempted to apply the concept to more categories, but with limited success due to the high cost of manual supervision. In this work, we introduce SHIC, a method to learn canonical maps without manual supervision which achieves better results than supervised methods for most categories. Our idea is to leverage foundation computer vision models such as DINO and Stable Diffusion that are open-ended and thus possess excellent priors over natural categories. SHIC reduces the problem of estimating image-to-template correspondences to predicting image-to-image correspondences using features from the foundation models. The reduction works by matching images of the object to non-photorealistic renders of the template, which emulates the process of collecting manual annotations for this task. These correspondences are then used to supervise high-quality canonical maps for any object of interest. We also show that image generators can further improve the realism of the template views, which provide an additional source of supervision for the model.
## QA:
coming soon
