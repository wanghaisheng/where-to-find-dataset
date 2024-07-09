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
- content: YeongHyeon Park et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-09 08:56:32'
tags:
- dataset
- all search terms
theme: light
title: Feature Attenuation of Defective Representation Can Resolve Incomplete Masking
  on Anomaly Detection
---

# title: Feature Attenuation of Defective Representation Can Resolve Incomplete Masking on Anomaly Detection 
## publish date: 
**2024-07-05** 
## authors: 
  YeongHyeon Park et.al. 
## paper id
2407.04597v1
## download
[2407.04597v1](http://arxiv.org/abs/2407.04597v1)
## abstracts:
In unsupervised anomaly detection (UAD) research, while state-of-the-art models have reached a saturation point with extensive studies on public benchmark datasets, they adopt large-scale tailor-made neural networks (NN) for detection performance or pursued unified models for various tasks. Towards edge computing, it is necessary to develop a computationally efficient and scalable solution that avoids large-scale complex NNs. Motivated by this, we aim to optimize the UAD performance with minimal changes to NN settings. Thus, we revisit the reconstruction-by-inpainting approach and rethink to improve it by analyzing strengths and weaknesses. The strength of the SOTA methods is a single deterministic masking approach that addresses the challenges of random multiple masking that is inference latency and output inconsistency. Nevertheless, the issue of failure to provide a mask to completely cover anomalous regions is a remaining weakness. To mitigate this issue, we propose Feature Attenuation of Defective Representation (FADeR) that only employs two MLP layers which attenuates feature information of anomaly reconstruction during decoding. By leveraging FADeR, features of unseen anomaly patterns are reconstructed into seen normal patterns, reducing false alarms. Experimental results demonstrate that FADeR achieves enhanced performance compared to similar-scale NNs. Furthermore, our approach exhibits scalability in performance enhancement when integrated with other single deterministic masking methods in a plug-and-play manner.
## QA:
coming soon
