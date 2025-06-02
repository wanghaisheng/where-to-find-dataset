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
- content: Heli Ben-Hamu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-02 11:46:00'
tags:
- dataset on github
- all search terms
theme: light
title: Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking
---

# title: Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking 
## publish date: 
**2025-05-30** 
## authors: 
  Heli Ben-Hamu et.al. 
## paper id
2505.24857v1
## download
[2505.24857v1](http://arxiv.org/abs/2505.24857v1)
## abstracts:
Recent masked diffusion models (MDMs) have shown competitive performance compared to autoregressive models (ARMs) for language modeling. While most literature has focused on performance enhancing sampling procedures, efficient sampling from MDMs has been scarcely explored. We make the observation that often a given sequence of partially masked tokens determines the values of multiple unknown tokens deterministically, meaning that a single prediction of a masked model holds additional information unused by standard sampling procedures. Based on this observation, we introduce EB-Sampler, a simple drop-in replacement for existing samplers, utilizing an Entropy Bounded unmasking procedure that dynamically unmasks multiple tokens in one function evaluation with predefined approximate error tolerance. We formulate the EB-Sampler as part of a broad family of adaptive samplers for which we provide an error analysis that motivates our algorithmic choices. EB-Sampler accelerates sampling from current state of the art MDMs by roughly 2-3x on standard coding and math reasoning benchmarks without loss in performance. We also validate the same procedure works well on smaller reasoning tasks including maze navigation and Sudoku, tasks ARMs often struggle with.
## QA:
coming soon
