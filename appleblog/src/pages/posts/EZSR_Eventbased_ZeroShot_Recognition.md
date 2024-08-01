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
- content: Yan Yang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-02 01:35:22'
tags:
- all search terms
- dataset
theme: light
title: EZSR Eventbased ZeroShot Recognition
---

# title: EZSR Eventbased ZeroShot Recognition 
## publish date: 
**2024-07-31** 
## authors: 
  Yan Yang et.al. 
## paper id
2407.21616v1
## download
[2407.21616v1](http://arxiv.org/abs/2407.21616v1)
## abstracts:
This paper studies zero-shot object recognition using event camera data. Guided by CLIP, which is pre-trained on RGB images, existing approaches achieve zero-shot object recognition by maximizing embedding similarities between event data encoded by an event encoder and RGB images encoded by the CLIP image encoder. Alternatively, several methods learn RGB frame reconstructions from event data for the CLIP image encoder. However, these approaches often result in suboptimal zero-shot performance.   This study develops an event encoder without relying on additional reconstruction networks. We theoretically analyze the performance bottlenecks of previous approaches: global similarity-based objective (i.e., maximizing the embedding similarities) cause semantic misalignments between the learned event embedding space and the CLIP text embedding space due to the degree of freedom. To mitigate the issue, we explore a scalar-wise regularization strategy. Furthermore, to scale up the number of events and RGB data pairs for training, we also propose a pipeline for synthesizing event data from static RGB images.   Experimentally, our data synthesis strategy exhibits an attractive scaling property, and our method achieves superior zero-shot object recognition performance on extensive standard benchmark datasets, even compared with past supervised learning approaches. For example, we achieve 47.84% zero-shot accuracy on the N-ImageNet dataset.
## QA:
coming soon
