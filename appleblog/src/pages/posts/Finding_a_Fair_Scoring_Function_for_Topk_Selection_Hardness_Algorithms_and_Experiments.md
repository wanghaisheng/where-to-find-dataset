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
- content: Guangya Cai et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-17 11:38:45'
tags:
- dataset
- all search terms
theme: light
title: Finding a Fair Scoring Function for Topk Selection Hardness Algorithms and
  Experiments
---

# title: Finding a Fair Scoring Function for Topk Selection Hardness Algorithms and Experiments 
## publish date: 
**2025-03-14** 
## authors: 
  Guangya Cai et.al. 
## paper id
2503.11575v1
## download
[2503.11575v1](http://arxiv.org/abs/2503.11575v1)
## abstracts:
Selecting a subset of the $k$ "best" items from a dataset of $n$ items, based on a scoring function, is a key task in decision-making. Given the widespread use of automated decision-making software nowadays, it is important that the outcome of this process, called top-$k$ selection, is fair. Here we consider the problem of identifying a linear scoring function for top-$k$ selection that is fair. The function computes a score for each item as a weighted sum of its (numerical) attribute values. Additionally, the function must ensure that the subset selected is a faithful representative of the entire dataset for a minority or historically disadvantaged group. Existing algorithms do not scale effectively on large, high-dimensional datasets. Our theoretical analysis shows that in more than two dimensions, no algorithm is likely to achieve good scalability with respect to dataset size (i.e., a run time of $O(n\cdot \text{polylog}(n))$), and the computational complexity is likely to increase rapidly with dimensionality. However, there are exceptions for small values of $k$ and for this case we provide significantly faster algorithms. We also provide efficient practical variants of these algorithms. Our implementations of these take advantage of modern hardware (e.g., exploiting parallelism). For large values of $k$, we give an alternative algorithm that, while theoretically worse, performs better in practice. Experimental results on real-world datasets demonstrate the efficiency of our proposed algorithms, which achieve speed-ups of up to several orders of magnitude compared to the state of the art (SoTA).
## QA:
coming soon
