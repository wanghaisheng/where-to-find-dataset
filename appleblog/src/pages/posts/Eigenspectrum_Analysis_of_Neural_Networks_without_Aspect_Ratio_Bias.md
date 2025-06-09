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
- content: Yuanzhe Hu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-09 11:46:01'
tags:
- all search terms
- dataset on github
theme: light
title: Eigenspectrum Analysis of Neural Networks without Aspect Ratio Bias
---

# title: Eigenspectrum Analysis of Neural Networks without Aspect Ratio Bias 
## publish date: 
**2025-06-06** 
## authors: 
  Yuanzhe Hu et.al. 
## paper id
2506.06280v1
## download
[2506.06280v1](http://arxiv.org/abs/2506.06280v1)
## abstracts:
Diagnosing deep neural networks (DNNs) through the eigenspectrum of weight matrices has been an active area of research in recent years. At a high level, eigenspectrum analysis of DNNs involves measuring the heavytailness of the empirical spectral densities (ESD) of weight matrices. It provides insight into how well a model is trained and can guide decisions on assigning better layer-wise training hyperparameters. In this paper, we address a challenge associated with such eigenspectrum methods: the impact of the aspect ratio of weight matrices on estimated heavytailness metrics. We demonstrate that matrices of varying sizes (and aspect ratios) introduce a non-negligible bias in estimating heavytailness metrics, leading to inaccurate model diagnosis and layer-wise hyperparameter assignment. To overcome this challenge, we propose FARMS (Fixed-Aspect-Ratio Matrix Subsampling), a method that normalizes the weight matrices by subsampling submatrices with a fixed aspect ratio. Instead of measuring the heavytailness of the original ESD, we measure the average ESD of these subsampled submatrices. We show that measuring the heavytailness of these submatrices with the fixed aspect ratio can effectively mitigate the aspect ratio bias. We validate our approach across various optimization techniques and application domains that involve eigenspectrum analysis of weights, including image classification in computer vision (CV) models, scientific machine learning (SciML) model training, and large language model (LLM) pruning. Our results show that despite its simplicity, FARMS uniformly improves the accuracy of eigenspectrum analysis while enabling more effective layer-wise hyperparameter assignment in these application domains. In one of the LLM pruning experiments, FARMS reduces the perplexity of the LLaMA-7B model by 17.3% when compared with the state-of-the-art method.
## QA:
coming soon
