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
- content: Zizheng Guo et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-05 11:32:45'
tags:
- all search terms
- dataset
theme: light
title: Data Debugging is NPhard for Classifiers Trained with SGD
---

# title: Data Debugging is NPhard for Classifiers Trained with SGD 
## publish date: 
**2024-08-02** 
## authors: 
  Zizheng Guo et.al. 
## paper id
2408.01365v1
## download
[2408.01365v1](http://arxiv.org/abs/2408.01365v1)
## abstracts:
Data debugging is to find a subset of the training data such that the model obtained by retraining on the subset has a better accuracy. A bunch of heuristic approaches are proposed, however, none of them are guaranteed to solve this problem effectively. This leaves an open issue whether there exists an efficient algorithm to find the subset such that the model obtained by retraining on it has a better accuracy. To answer this open question and provide theoretical basis for further study on developing better algorithms for data debugging, we investigate the computational complexity of the problem named Debuggable. Given a machine learning model $\mathcal{M}$ obtained by training on dataset $D$ and a test instance $(\mathbf{x}_\text{test},y_\text{test})$ where $\mathcal{M}(\mathbf{x}_\text{test})\neq y_\text{test}$, Debuggable is to determine whether there exists a subset $D^\prime$ of $D$ such that the model $\mathcal{M}^\prime$ obtained by retraining on $D^\prime$ satisfies $\mathcal{M}^\prime(\mathbf{x}_\text{test})=y_\text{test}$. To cover a wide range of commonly used models, we take SGD-trained linear classifier as the model and derive the following main results. (1) If the loss function and the dimension of the model are not fixed, Debuggable is NP-complete regardless of the training order in which all the training samples are processed during SGD. (2) For hinge-like loss functions, a comprehensive analysis on the computational complexity of Debuggable is provided; (3) If the loss function is a linear function, Debuggable can be solved in linear time, that is, data debugging can be solved easily in this case. These results not only highlight the limitations of current approaches but also offer new insights into data debugging.
## QA:
coming soon
