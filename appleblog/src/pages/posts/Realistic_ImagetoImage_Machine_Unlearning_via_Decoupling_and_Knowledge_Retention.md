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
- content: Ayush K. Varshney et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-10 11:35:43'
tags:
- all search terms
- dataset
theme: light
title: Realistic ImagetoImage Machine Unlearning via Decoupling and Knowledge Retention
---

# title: Realistic ImagetoImage Machine Unlearning via Decoupling and Knowledge Retention 
## publish date: 
**2025-02-06** 
## authors: 
  Ayush K. Varshney et.al. 
## paper id
2502.04260v1
## download
[2502.04260v1](http://arxiv.org/abs/2502.04260v1)
## abstracts:
Machine Unlearning allows participants to remove their data from a trained machine learning model in order to preserve their privacy, and security. However, the machine unlearning literature for generative models is rather limited. The literature for image-to-image generative model (I2I model) considers minimizing the distance between Gaussian noise and the output of I2I model for forget samples as machine unlearning. However, we argue that the machine learning model performs fairly well on unseen data i.e., a retrained model will be able to catch generic patterns in the data and hence will not generate an output which is equivalent to Gaussian noise. In this paper, we consider that the model after unlearning should treat forget samples as out-of-distribution (OOD) data, i.e., the unlearned model should no longer recognize or encode the specific patterns found in the forget samples. To achieve this, we propose a framework which decouples the model parameters with gradient ascent, ensuring that forget samples are OOD for unlearned model with theoretical guarantee. We also provide $(\epsilon, \delta)$-unlearning guarantee for model updates with gradient ascent. The unlearned model is further fine-tuned on the remaining samples to maintain its performance. We also propose an attack model to ensure that the unlearned model has effectively removed the influence of forget samples. Extensive empirical evaluation on two large-scale datasets, ImageNet-1K and Places365 highlights the superiority of our approach. To show comparable performance with retrained model, we also show the comparison of a simple AutoEncoder on various baselines on CIFAR-10 dataset.
## QA:
coming soon
