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
- content: Aryan Yazdan Parast et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-24 11:39:31'
tags:
- dataset
- all search terms
theme: light
title: Leveraging TexttoImage Generation for Handling Spurious Correlation
---

# title: Leveraging TexttoImage Generation for Handling Spurious Correlation 
## publish date: 
**2025-03-21** 
## authors: 
  Aryan Yazdan Parast et.al. 
## paper id
2503.17226v1
## download
[2503.17226v1](http://arxiv.org/abs/2503.17226v1)
## abstracts:
Deep neural networks trained with Empirical Risk Minimization (ERM) perform well when both training and test data come from the same domain, but they often fail to generalize to out-of-distribution samples. In image classification, these models may rely on spurious correlations that often exist between labels and irrelevant features of images, making predictions unreliable when those features do not exist. We propose a technique to generate training samples with text-to-image (T2I) diffusion models for addressing the spurious correlation problem. First, we compute the best describing token for the visual features pertaining to the causal components of samples by a textual inversion mechanism. Then, leveraging a language segmentation method and a diffusion model, we generate new samples by combining the causal component with the elements from other classes. We also meticulously prune the generated samples based on the prediction probabilities and attribution scores of the ERM model to ensure their correct composition for our objective. Finally, we retrain the ERM model on our augmented dataset. This process reduces the model's reliance on spurious correlations by learning from carefully crafted samples for in which this correlation does not exist. Our experiments show that across different benchmarks, our technique achieves better worst-group accuracy than the existing state-of-the-art methods.
## QA:
coming soon
