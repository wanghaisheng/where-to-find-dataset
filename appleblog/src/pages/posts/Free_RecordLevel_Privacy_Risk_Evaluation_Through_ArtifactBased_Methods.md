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
- content: Joseph Pollock et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-11 11:35:22'
tags:
- all search terms
- dataset
theme: light
title: Free RecordLevel Privacy Risk Evaluation Through ArtifactBased Methods
---

# title: Free RecordLevel Privacy Risk Evaluation Through ArtifactBased Methods 
## publish date: 
**2024-11-08** 
## authors: 
  Joseph Pollock et.al. 
## paper id
2411.05743v1
## download
[2411.05743v1](http://arxiv.org/abs/2411.05743v1)
## abstracts:
Membership inference attacks (MIAs) are widely used to empirically assess the privacy risks of samples used to train a target machine learning model. State-of-the-art methods however require training hundreds of shadow models, with the same size and architecture of the target model, solely to evaluate the privacy risk. While one might be able to afford this for small models, the cost often becomes prohibitive for medium and large models.   We here instead propose a novel approach to identify the at-risk samples using only artifacts available during training, with little to no additional computational overhead. Our method analyzes individual per-sample loss traces and uses them to identify the vulnerable data samples. We demonstrate the effectiveness of our artifact-based approach through experiments on the CIFAR10 dataset, showing high precision in identifying vulnerable samples as determined by a SOTA shadow model-based MIA (LiRA). Impressively, our method reaches the same precision as another SOTA MIA when measured against LiRA, despite it being orders of magnitude cheaper. We then show LT-IQR to outperform alternative loss aggregation methods, perform ablation studies on hyperparameters, and validate the robustness of our method to the target metric. Finally, we study the evolution of the vulnerability score distribution throughout training as a metric for model-level risk assessment.
## QA:
coming soon
