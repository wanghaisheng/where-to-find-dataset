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
- content: Samarth N Ramesh et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-25 11:39:20'
tags:
- all search terms
- dataset on github
theme: light
title: Efficient Pruning of TexttoImage Models Insights from Pruning Stable Diffusion
---

# title: Efficient Pruning of TexttoImage Models Insights from Pruning Stable Diffusion 
## publish date: 
**2024-11-22** 
## authors: 
  Samarth N Ramesh et.al. 
## paper id
2411.15113v1
## download
[2411.15113v1](http://arxiv.org/abs/2411.15113v1)
## abstracts:
As text-to-image models grow increasingly powerful and complex, their burgeoning size presents a significant obstacle to widespread adoption, especially on resource-constrained devices. This paper presents a pioneering study on post-training pruning of Stable Diffusion 2, addressing the critical need for model compression in text-to-image domain. Our study tackles the pruning techniques for the previously unexplored multi-modal generation models, and particularly examines the pruning impact on the textual component and the image generation component separately. We conduct a comprehensive comparison on pruning the model or the single component of the model in various sparsities. Our results yield previously undocumented findings. For example, contrary to established trends in language model pruning, we discover that simple magnitude pruning outperforms more advanced techniques in text-to-image context. Furthermore, our results show that Stable Diffusion 2 can be pruned to 38.5% sparsity with minimal quality loss, achieving a significant reduction in model size. We propose an optimal pruning configuration that prunes the text encoder to 47.5% and the diffusion generator to 35%. This configuration maintains image generation quality while substantially reducing computational requirements. In addition, our work uncovers intriguing questions about information encoding in text-to-image models: we observe that pruning beyond certain thresholds leads to sudden performance drops (unreadable images), suggesting that specific weights encode critical semantics information. This finding opens new avenues for future research in model compression, interoperability, and bias identification in text-to-image models. By providing crucial insights into the pruning behavior of text-to-image models, our study lays the groundwork for developing more efficient and accessible AI-driven image generation systems
## QA:
coming soon
