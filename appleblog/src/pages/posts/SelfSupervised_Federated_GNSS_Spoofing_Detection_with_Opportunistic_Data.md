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
- content: Wenjie Liu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-12 11:43:53'
tags:
- dataset
- all search terms
theme: light
title: SelfSupervised Federated GNSS Spoofing Detection with Opportunistic Data
---

# title: SelfSupervised Federated GNSS Spoofing Detection with Opportunistic Data 
## publish date: 
**2025-05-09** 
## authors: 
  Wenjie Liu et.al. 
## paper id
2505.06171v1
## download
[2505.06171v1](http://arxiv.org/abs/2505.06171v1)
## abstracts:
Global navigation satellite systems (GNSS) are vulnerable to spoofing attacks, with adversarial signals manipulating the location or time information of receivers, potentially causing severe disruptions. The task of discerning the spoofing signals from benign ones is naturally relevant for machine learning, thus recent interest in applying it for detection. While deep learning-based methods are promising, they require extensive labeled datasets, consume significant computational resources, and raise privacy concerns due to the sensitive nature of position data. This is why this paper proposes a self-supervised federated learning framework for GNSS spoofing detection. It consists of a cloud server and local mobile platforms. Each mobile platform employs a self-supervised anomaly detector using long short-term memory (LSTM) networks. Labels for training are generated locally through a spoofing-deviation prediction algorithm, ensuring privacy. Local models are trained independently, and only their parameters are uploaded to the cloud server, which aggregates them into a global model using FedAvg. The updated global model is then distributed back to the mobile platforms and trained iteratively. The evaluation shows that our self-supervised federated learning framework outperforms position-based and deep learning-based methods in detecting spoofing attacks while preserving data privacy.
## QA:
coming soon
