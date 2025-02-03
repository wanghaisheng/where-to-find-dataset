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
- content: Liudi Yang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-03 11:34:55'
tags:
- all search terms
- dataset on github
theme: light
title: LiDAR Loop Closure Detection using Semantic Graphs with Graph Attention Networks
---

# title: LiDAR Loop Closure Detection using Semantic Graphs with Graph Attention Networks 
## publish date: 
**2025-01-31** 
## authors: 
  Liudi Yang et.al. 
## paper id
2501.19382v1
## download
[2501.19382v1](http://arxiv.org/abs/2501.19382v1)
## abstracts:
In this paper, we propose a novel loop closure detection algorithm that uses graph attention neural networks to encode semantic graphs to perform place recognition and then use semantic registration to estimate the 6 DoF relative pose constraint. Our place recognition algorithm has two key modules, namely, a semantic graph encoder module and a graph comparison module. The semantic graph encoder employs graph attention networks to efficiently encode spatial, semantic and geometric information from the semantic graph of the input point cloud. We then use self-attention mechanism in both node-embedding and graph-embedding steps to create distinctive graph vectors. The graph vectors of the current scan and a keyframe scan are then compared in the graph comparison module to identify a possible loop closure. Specifically, employing the difference of the two graph vectors showed a significant improvement in performance, as shown in ablation studies. Lastly, we implemented a semantic registration algorithm that takes in loop closure candidate scans and estimates the relative 6 DoF pose constraint for the LiDAR SLAM system. Extensive evaluation on public datasets shows that our model is more accurate and robust, achieving 13% improvement in maximum F1 score on the SemanticKITTI dataset, when compared to the baseline semantic graph algorithm. For the benefit of the community, we open-source the complete implementation of our proposed algorithm and custom implementation of semantic registration at https://github.com/crepuscularlight/SemanticLoopClosure
## QA:
coming soon
