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
- content: Jiachang Liu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-17 11:35:41'
tags:
- dataset
- all search terms
theme: light
title: Scalable Firstorder Method for Certifying Optimal kSparse GLMs
---

# title: Scalable Firstorder Method for Certifying Optimal kSparse GLMs 
## publish date: 
**2025-02-13** 
## authors: 
  Jiachang Liu et.al. 
## paper id
2502.09502v1
## download
[2502.09502v1](http://arxiv.org/abs/2502.09502v1)
## abstracts:
This paper investigates the problem of certifying optimality for sparse generalized linear models (GLMs), where sparsity is enforced through an $\ell_0$ cardinality constraint. While branch-and-bound (BnB) frameworks can certify optimality by pruning nodes using dual bounds, existing methods for computing these bounds are either computationally intensive or exhibit slow convergence, limiting their scalability to large-scale problems. To address this challenge, we propose a first-order proximal gradient algorithm designed to solve the perspective relaxation of the problem within a BnB framework. Specifically, we formulate the relaxed problem as a composite optimization problem and demonstrate that the proximal operator of the non-smooth component can be computed exactly in log-linear time complexity, eliminating the need to solve a computationally expensive second-order cone program. Furthermore, we introduce a simple restart strategy that enhances convergence speed while maintaining low per-iteration complexity. Extensive experiments on synthetic and real-world datasets show that our approach significantly accelerates dual bound computations and is highly effective in providing optimality certificates for large-scale problems.
## QA:
coming soon
