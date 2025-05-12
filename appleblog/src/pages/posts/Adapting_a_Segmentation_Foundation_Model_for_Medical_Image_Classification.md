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
- content: Pengfei Gu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-12 11:43:51'
tags:
- dataset
- all search terms
theme: light
title: Adapting a Segmentation Foundation Model for Medical Image Classification
---

# title: Adapting a Segmentation Foundation Model for Medical Image Classification 
## publish date: 
**2025-05-09** 
## authors: 
  Pengfei Gu et.al. 
## paper id
2505.06217v1
## download
[2505.06217v1](http://arxiv.org/abs/2505.06217v1)
## abstracts:
Recent advancements in foundation models, such as the Segment Anything Model (SAM), have shown strong performance in various vision tasks, particularly image segmentation, due to their impressive zero-shot segmentation capabilities. However, effectively adapting such models for medical image classification is still a less explored topic. In this paper, we introduce a new framework to adapt SAM for medical image classification. First, we utilize the SAM image encoder as a feature extractor to capture segmentation-based features that convey important spatial and contextual details of the image, while freezing its weights to avoid unnecessary overhead during training. Next, we propose a novel Spatially Localized Channel Attention (SLCA) mechanism to compute spatially localized attention weights for the feature maps. The features extracted from SAM's image encoder are processed through SLCA to compute attention weights, which are then integrated into deep learning classification models to enhance their focus on spatially relevant or meaningful regions of the image, thus improving classification performance. Experimental results on three public medical image classification datasets demonstrate the effectiveness and data-efficiency of our approach.
## QA:
coming soon
