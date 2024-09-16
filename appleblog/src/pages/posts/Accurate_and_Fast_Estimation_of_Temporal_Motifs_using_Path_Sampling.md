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
- content: Yunjie Pan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-16 11:36:08'
tags:
- dataset
- all search terms
theme: light
title: Accurate and Fast Estimation of Temporal Motifs using Path Sampling
---

# title: Accurate and Fast Estimation of Temporal Motifs using Path Sampling 
## publish date: 
**2024-09-13** 
## authors: 
  Yunjie Pan et.al. 
## paper id
2409.08975v1
## download
[2409.08975v1](http://arxiv.org/abs/2409.08975v1)
## abstracts:
Counting the number of small subgraphs, called motifs, is a fundamental problem in social network analysis and graph mining. Many real-world networks are directed and temporal, where edges have timestamps. Motif counting in directed, temporal graphs is especially challenging because there are a plethora of different kinds of patterns. Temporal motif counts reveal much richer information and there is a need for scalable algorithms for motif counting.   A major challenge in counting is that there can be trillions of temporal motif matches even with a graph with only millions of vertices. Both the motifs and the input graphs can have multiple edges between two vertices, leading to a combinatorial explosion problem. Counting temporal motifs involving just four vertices is not feasible with current state-of-the-art algorithms.   We design an algorithm, TEACUPS, that addresses this problem using a novel technique of temporal path sampling. We combine a path sampling method with carefully designed temporal data structures, to propose an efficient approximate algorithm for temporal motif counting. TEACUPS is an unbiased estimator with provable concentration behavior, which can be used to bound the estimation error. For a Bitcoin graph with hundreds of millions of edges, TEACUPS runs in less than 1 minute, while the exact counting algorithm takes more than a day. We empirically demonstrate the accuracy of TEACUPS on large datasets, showing an average of 30$\times$ speedup (up to 2000$\times$ speedup) compared to existing GPU-based exact counting methods while preserving high count estimation accuracy.
## QA:
coming soon
