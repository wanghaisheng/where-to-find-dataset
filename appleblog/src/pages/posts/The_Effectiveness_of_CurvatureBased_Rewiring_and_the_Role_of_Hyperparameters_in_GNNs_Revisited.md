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
- content: Floriano Tori et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-15 11:33:18'
tags:
- all search terms
- dataset
theme: light
title: The Effectiveness of CurvatureBased Rewiring and the Role of Hyperparameters
  in GNNs Revisited
---

# title: The Effectiveness of CurvatureBased Rewiring and the Role of Hyperparameters in GNNs Revisited 
## publish date: 
**2024-07-12** 
## authors: 
  Floriano Tori et.al. 
## paper id
2407.09381v1
## download
[2407.09381v1](http://arxiv.org/abs/2407.09381v1)
## abstracts:
Message passing is the dominant paradigm in Graph Neural Networks (GNNs). The efficiency of message passing, however, can be limited by the topology of the graph. This happens when information is lost during propagation due to being oversquashed when travelling through bottlenecks. To remedy this, recent efforts have focused on graph rewiring techniques, which disconnect the input graph originating from the data and the computational graph, on which message passing is performed. A prominent approach for this is to use discrete graph curvature measures, of which several variants have been proposed, to identify and rewire around bottlenecks, facilitating information propagation. While oversquashing has been demonstrated in synthetic datasets, in this work we reevaluate the performance gains that curvature-based rewiring brings to real-world datasets. We show that in these datasets, edges selected during the rewiring process are not in line with theoretical criteria identifying bottlenecks. This implies they do not necessarily oversquash information during message passing. Subsequently, we demonstrate that SOTA accuracies on these datasets are outliers originating from sweeps of hyperparameters -- both the ones for training and dedicated ones related to the rewiring algorithm -- instead of consistent performance gains. In conclusion, our analysis nuances the effectiveness of curvature-based rewiring in real-world datasets and brings a new perspective on the methods to evaluate GNN accuracy improvements.
## QA:
coming soon