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
- content: Sandeep Nagar et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-21 11:37:23'
tags:
- all search terms
- dataset
theme: light
title: Parallel Backpropagation for Inverse of a Convolution with Application to Normalizing
  Flows
---

# title: Parallel Backpropagation for Inverse of a Convolution with Application to Normalizing Flows 
## publish date: 
**2024-10-18** 
## authors: 
  Sandeep Nagar et.al. 
## paper id
2410.14634v1
## download
[2410.14634v1](http://arxiv.org/abs/2410.14634v1)
## abstracts:
Inverse of an invertible convolution is an important operation that comes up in Normalizing Flows, Image Deblurring, etc. The naive algorithm for backpropagation of this operation using Gaussian elimination has running time $O(n^3)$ where $n$ is the number of pixels in the image. We give a fast parallel backpropagation algorithm with running time $O(\sqrt{n})$ for a square image and provide a GPU implementation of the same. Inverse Convolutions are usually used in Normalizing Flows in the sampling pass, making them slow. We propose to use Inverse Convolutions in the forward (image to latent vector) pass of the Normalizing flow. Since the sampling pass is the inverse of the forward pass, it will use convolutions only, resulting in efficient sampling times. We use our parallel backpropagation algorithm for optimizing the inverse convolution layer resulting in fast training times also. We implement this approach in various Normalizing Flow backbones, resulting in our Inverse-Flow models. We benchmark Inverse-Flow on standard datasets and show significantly improved sampling times with similar bits per dimension compared to previous models.
## QA:
coming soon
