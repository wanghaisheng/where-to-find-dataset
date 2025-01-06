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
- content: Z. Zhang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-01-06 11:36:59'
tags:
- all search terms
- dataset
theme: light
title: Testtime Controllable Image Generation by Explicit Spatial Constraint Enforcement
---

# title: Testtime Controllable Image Generation by Explicit Spatial Constraint Enforcement 
## publish date: 
**2025-01-02** 
## authors: 
  Z. Zhang et.al. 
## paper id
2501.01368v1
## download
[2501.01368v1](http://arxiv.org/abs/2501.01368v1)
## abstracts:
Recent text-to-image generation favors various forms of spatial conditions, e.g., masks, bounding boxes, and key points. However, the majority of the prior art requires form-specific annotations to fine-tune the original model, leading to poor test-time generalizability. Meanwhile, existing training-free methods work well only with simplified prompts and spatial conditions. In this work, we propose a novel yet generic test-time controllable generation method that aims at natural text prompts and complex conditions. Specifically, we decouple spatial conditions into semantic and geometric conditions and then enforce their consistency during the image-generation process individually. As for the former, we target bridging the gap between the semantic condition and text prompts, as well as the gap between such condition and the attention map from diffusion models. To achieve this, we propose to first complete the prompt w.r.t. semantic condition, and then remove the negative impact of distracting prompt words by measuring their statistics in attention maps as well as distances in word space w.r.t. this condition. To further cope with the complex geometric conditions, we introduce a geometric transform module, in which Region-of-Interests will be identified in attention maps and further used to translate category-wise latents w.r.t. geometric condition. More importantly, we propose a diffusion-based latents-refill method to explicitly remove the impact of latents at the RoI, reducing the artifacts on generated images. Experiments on Coco-stuff dataset showcase 30$\%$ relative boost compared to SOTA training-free methods on layout consistency evaluation metrics.
## QA:
coming soon
