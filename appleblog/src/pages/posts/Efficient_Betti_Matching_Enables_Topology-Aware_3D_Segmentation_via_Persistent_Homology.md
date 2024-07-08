---
layout: '../../layouts/MarkdownPost.astro'
title: '**Efficient Betti Matching Enables Topology-Aware 3D Segmentation via Persistent Homology**'
pubDate: '2024-07-09 06:54:41'
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: '['dataset', 'all search terms']' 
theme: 'light'
featured: true

meta:
 - name: author
   content: Nico Stucki et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04683v1
## download
[2407.04683v1](http://arxiv.org/abs/2407.04683v1)
## abstracts:
In this work, we propose an efficient algorithm for the calculation of the Betti matching, which can be used as a loss function to train topology aware segmentation networks. Betti matching loss builds on techniques from topological data analysis, specifically persistent homology. A major challenge is the computational cost of computing persistence barcodes. In response to this challenge, we propose a new, highly optimized implementation of Betti matching, implemented in C++ together with a python interface, which achieves significant speedups compared to the state-of-the-art implementation Cubical Ripser. We use Betti matching 3D to train segmentation networks with the Betti matching loss and demonstrate improved topological correctness of predicted segmentations across several datasets. The source code is available at https://github.com/nstucki/Betti-Matching-3D.
## QA:
coming soon
