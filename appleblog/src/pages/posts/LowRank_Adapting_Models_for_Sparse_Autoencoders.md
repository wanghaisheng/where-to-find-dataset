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
- content: Matthew Chen et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-03 11:34:50'
tags:
- all search terms
- dataset on github
theme: light
title: LowRank Adapting Models for Sparse Autoencoders
---

# title: LowRank Adapting Models for Sparse Autoencoders 
## publish date: 
**2025-01-31** 
## authors: 
  Matthew Chen et.al. 
## paper id
2501.19406v1
## download
[2501.19406v1](http://arxiv.org/abs/2501.19406v1)
## abstracts:
Sparse autoencoders (SAEs) decompose language model representations into a sparse set of linear latent vectors. Recent works have improved SAEs using language model gradients, but these techniques require many expensive backward passes during training and still cause a significant increase in cross entropy loss when SAE reconstructions are inserted into the model. In this work, we improve on these limitations by taking a fundamentally different approach: we use low-rank adaptation (LoRA) to finetune the language model itself around a previously trained SAE. We analyze our method across SAE sparsity, SAE width, language model size, LoRA rank, and model layer on the Gemma Scope family of SAEs. In these settings, our method reduces the cross entropy loss gap by 30% to 55% when SAEs are inserted during the forward pass. We also find that compared to end-to-end (e2e) SAEs, our approach achieves the same downstream cross entropy loss 3$\times$ to 20$\times$ faster on Gemma-2-2B and 2$\times$ to 10$\times$ faster on Llama-3.2-1B. We further show that our technique improves downstream metrics and can adapt multiple SAEs at once. Our results demonstrate that improving model interpretability is not limited to post-hoc SAE training; Pareto improvements can also be achieved by directly optimizing the model itself.
## QA:
coming soon
