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
- content: Hongxiang Zhang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-07 11:36:39'
tags:
- dataset
- all search terms
theme: light
title: SteerDiff Steering towards Safe TexttoImage Diffusion Models
---

# title: SteerDiff Steering towards Safe TexttoImage Diffusion Models 
## publish date: 
**2024-10-03** 
## authors: 
  Hongxiang Zhang et.al. 
## paper id
2410.02710v1
## download
[2410.02710v1](http://arxiv.org/abs/2410.02710v1)
## abstracts:
Text-to-image (T2I) diffusion models have drawn attention for their ability to generate high-quality images with precise text alignment. However, these models can also be misused to produce inappropriate content. Existing safety measures, which typically rely on text classifiers or ControlNet-like approaches, are often insufficient. Traditional text classifiers rely on large-scale labeled datasets and can be easily bypassed by rephrasing. As diffusion models continue to scale, fine-tuning these safeguards becomes increasingly challenging and lacks flexibility. Recent red-teaming attack researches further underscore the need for a new paradigm to prevent the generation of inappropriate content. In this paper, we introduce SteerDiff, a lightweight adaptor module designed to act as an intermediary between user input and the diffusion model, ensuring that generated images adhere to ethical and safety standards with little to no impact on usability. SteerDiff identifies and manipulates inappropriate concepts within the text embedding space to guide the model away from harmful outputs. We conduct extensive experiments across various concept unlearning tasks to evaluate the effectiveness of our approach. Furthermore, we benchmark SteerDiff against multiple red-teaming strategies to assess its robustness. Finally, we explore the potential of SteerDiff for concept forgetting tasks, demonstrating its versatility in text-conditioned image generation.
## QA:
coming soon
