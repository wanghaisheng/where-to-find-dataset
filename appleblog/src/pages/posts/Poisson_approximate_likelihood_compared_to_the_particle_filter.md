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
- content: Yize Hao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-23 11:35:13'
tags:
- dataset
- all search terms
theme: light
title: Poisson approximate likelihood compared to the particle filter
---

# title: Poisson approximate likelihood compared to the particle filter 
## publish date: 
**2024-09-18** 
## authors: 
  Yize Hao et.al. 
## paper id
2409.12173v1
## download
[2409.12173v1](http://arxiv.org/abs/2409.12173v1)
## abstracts:
Filtering algorithms are fundamental for inference on partially observed stochastic dynamic systems, since they provide access to the likelihood function and hence enable likelihood-based or Bayesian inference. A novel Poisson approximate likelihood (PAL) filter was introduced by Whitehouse et al. (2023). PAL employs a Poisson approximation to conditional densities, offering a fast approximation to the likelihood function for a certain subset of partially observed Markov process models. A central piece of evidence for PAL is the comparison in Table 1 of Whitehouse et al. (2023), which claims a large improvement for PAL over a standard particle filter algorithm. This evidence, based on a model and data from a previous scientific study by Stocks et al. (2020), might suggest that researchers confronted with similar models should use PAL rather than particle filter methods. Taken at face value, this evidence also reduces the credibility of Stocks et al. (2020) by indicating a shortcoming with the numerical methods that they used. However, we show that the comparison of log-likelihood values made by Whitehouse et al. (2023) is flawed because their PAL calculations were carried out using a dataset scaled differently from the previous study. If PAL and the particle filter are applied to the same data, the advantage claimed for PAL disappears. On simulations where the model is correctly specified, the particle filter outperforms PAL.
## QA:
coming soon
