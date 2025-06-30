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
- content: Erkan Turan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-30 11:47:21'
tags:
- all search terms
- dataset
theme: light
title: Unfolding Generative Flows with Koopman Operators Fast and Interpretable Sampling
---

# title: Unfolding Generative Flows with Koopman Operators Fast and Interpretable Sampling 
## publish date: 
**2025-06-27** 
## authors: 
  Erkan Turan et.al. 
## paper id
2506.22304v1
## download
[2506.22304v1](http://arxiv.org/abs/2506.22304v1)
## abstracts:
Conditional Flow Matching (CFM) offers a simulation-free framework for training continuous-time generative models, bridging diffusion and flow-based approaches. However, sampling from CFM still relies on numerically solving non-linear ODEs which can be computationally expensive and difficult to interpret. Recent alternatives address sampling speed via trajectory straightening, mini-batch coupling or distillation. However, these methods typically do not shed light on the underlying \textit{structure} of the generative process. In this work, we propose to accelerate CFM and introduce an interpretable representation of its dynamics by integrating Koopman operator theory, which models non-linear flows as linear evolution in a learned space of observables. We introduce a decoder-free Koopman-CFM architecture that learns an embedding where the generative dynamics become linear, enabling closed-form, one-step sampling via matrix exponentiation. This results in significant speedups over traditional CFM as demonstrated on controlled 2D datasets and real-world benchmarks, MNIST, Fashion-MNIST (F-MNIST), and the Toronto Face Dataset (TFD). Unlike previous methods, our approach leads to a well-structured Koopman generator, whose spectral properties, eigenvalues, and eigenfunctions offer principled tools for analyzing generative behavior such as temporal scaling, mode stability, and decomposition in Koopman latent space. By combining sampling efficiency with analytical structure, Koopman-enhanced flow matching offers a potential step toward fast and interpretable generative modeling.
## QA:
coming soon
