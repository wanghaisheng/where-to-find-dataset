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
- content: Shoujin Huang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-02 01:35:23'
tags:
- all search terms
- dataset
theme: light
title: Robust Simultaneous Multislice MRI Reconstruction Using Deep Generative Priors
---

# title: Robust Simultaneous Multislice MRI Reconstruction Using Deep Generative Priors 
## publish date: 
**2024-07-31** 
## authors: 
  Shoujin Huang et.al. 
## paper id
2407.21600v1
## download
[2407.21600v1](http://arxiv.org/abs/2407.21600v1)
## abstracts:
Simultaneous multislice (SMS) imaging is a powerful technique for accelerating magnetic resonance imaging (MRI) acquisitions. However, SMS reconstruction remains challenging due to the complex signal interactions between and within the excited slices. This study presents a robust SMS MRI reconstruction method using deep generative priors. Starting from Gaussian noise, we leverage denoising diffusion probabilistic models (DDPM) to gradually recover the individual slices through reverse diffusion iterations while imposing data consistency from the measured k-space under readout concatenation framework. The posterior sampling procedure is designed such that the DDPM training can be performed on single-slice images without special adjustments for SMS tasks. Additionally, our method integrates a low-frequency enhancement (LFE) module to address a practical issue that SMS-accelerated fast spin echo (FSE) and echo-planar imaging (EPI) sequences cannot easily embed autocalibration signals. Extensive experiments demonstrate that our approach consistently outperforms existing methods and generalizes well to unseen datasets. The code is available at https://github.com/Solor-pikachu/ROGER after the review process.
## QA:
coming soon
