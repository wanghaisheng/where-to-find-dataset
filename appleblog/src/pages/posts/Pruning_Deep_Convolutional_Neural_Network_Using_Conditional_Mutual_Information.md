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
- content: Tien Vu-Van et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-02 11:40:40'
tags:
- all search terms
- dataset
theme: light
title: Pruning Deep Convolutional Neural Network Using Conditional Mutual Information
---

# title: Pruning Deep Convolutional Neural Network Using Conditional Mutual Information 
## publish date: 
**2024-11-27** 
## authors: 
  Tien Vu-Van et.al. 
## paper id
2411.18578v1
## download
[2411.18578v1](http://arxiv.org/abs/2411.18578v1)
## abstracts:
Convolutional Neural Networks (CNNs) achieve high performance in image classification tasks but are challenging to deploy on resource-limited hardware due to their large model sizes. To address this issue, we leverage Mutual Information, a metric that provides valuable insights into how deep learning models retain and process information through measuring the shared information between input features or output labels and network layers. In this study, we propose a structured filter-pruning approach for CNNs that identifies and selectively retains the most informative features in each layer. Our approach successively evaluates each layer by ranking the importance of its feature maps based on Conditional Mutual Information (CMI) values, computed using a matrix-based Renyi {\alpha}-order entropy numerical method. We propose several formulations of CMI to capture correlation among features across different layers. We then develop various strategies to determine the cutoff point for CMI values to prune unimportant features. This approach allows parallel pruning in both forward and backward directions and significantly reduces model size while preserving accuracy. Tested on the VGG16 architecture with the CIFAR-10 dataset, the proposed method reduces the number of filters by more than a third, with only a 0.32% drop in test accuracy.
## QA:
coming soon
