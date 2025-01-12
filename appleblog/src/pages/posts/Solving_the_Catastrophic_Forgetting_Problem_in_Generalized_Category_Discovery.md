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
- content: Xinzi Cao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-01-12 17:14:23'
tags:
- all search terms
- dataset
theme: light
title: Solving the Catastrophic Forgetting Problem in Generalized Category Discovery
---

# title: Solving the Catastrophic Forgetting Problem in Generalized Category Discovery 
## publish date: 
**2025-01-09** 
## authors: 
  Xinzi Cao et.al. 
## paper id
2501.05272v1
## download
[2501.05272v1](http://arxiv.org/abs/2501.05272v1)
## abstracts:
Generalized Category Discovery (GCD) aims to identify a mix of known and novel categories within unlabeled data sets, providing a more realistic setting for image recognition. Essentially, GCD needs to remember existing patterns thoroughly to recognize novel categories. Recent state-of-the-art method SimGCD transfers the knowledge from known-class data to the learning of novel classes through debiased learning. However, some patterns are catastrophically forgot during adaptation and thus lead to poor performance in novel categories classification. To address this issue, we propose a novel learning approach, LegoGCD, which is seamlessly integrated into previous methods to enhance the discrimination of novel classes while maintaining performance on previously encountered known classes. Specifically, we design two types of techniques termed as Local Entropy Regularization (LER) and Dual-views Kullback Leibler divergence constraint (DKL). The LER optimizes the distribution of potential known class samples in unlabeled data, thus ensuring the preservation of knowledge related to known categories while learning novel classes. Meanwhile, DKL introduces Kullback Leibler divergence to encourage the model to produce a similar prediction distribution of two view samples from the same image. In this way, it successfully avoids mismatched prediction and generates more reliable potential known class samples simultaneously. Extensive experiments validate that the proposed LegoGCD effectively addresses the known category forgetting issue across all datasets, eg, delivering a 7.74% and 2.51% accuracy boost on known and novel classes in CUB, respectively. Our code is available at: https://github.com/Cliffia123/LegoGCD.
## QA:
coming soon
