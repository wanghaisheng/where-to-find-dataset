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
- content: Parameswaran Kamalaruban et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-10 11:31:47'
tags:
- dataset
- all search terms
theme: light
title: FairnessAware LowRank Adaptation Under Demographic Privacy Constraints
---

# title: FairnessAware LowRank Adaptation Under Demographic Privacy Constraints 
## publish date: 
**2025-03-07** 
## authors: 
  Parameswaran Kamalaruban et.al. 
## paper id
2503.05684v1
## download
[2503.05684v1](http://arxiv.org/abs/2503.05684v1)
## abstracts:
Pre-trained foundation models can be adapted for specific tasks using Low-Rank Adaptation (LoRA). However, the fairness properties of these adapted classifiers remain underexplored. Existing fairness-aware fine-tuning methods rely on direct access to sensitive attributes or their predictors, but in practice, these sensitive attributes are often held under strict consumer privacy controls, and neither the attributes nor their predictors are available to model developers, hampering the development of fair models. To address this issue, we introduce a set of LoRA-based fine-tuning methods that can be trained in a distributed fashion, where model developers and fairness auditors collaborate without sharing sensitive attributes or predictors. In this paper, we evaluate three such methods - sensitive unlearning, adversarial training, and orthogonality loss - against a fairness-unaware baseline, using experiments on the CelebA and UTK-Face datasets with an ImageNet pre-trained ViT-Base model. We find that orthogonality loss consistently reduces bias while maintaining or improving utility, whereas adversarial training improves False Positive Rate Parity and Demographic Parity in some cases, and sensitive unlearning provides no clear benefit. In tasks where significant biases are present, distributed fairness-aware fine-tuning methods can effectively eliminate bias without compromising consumer privacy and, in most cases, improve model utility.
## QA:
coming soon
