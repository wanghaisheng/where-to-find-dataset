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
- content: Shih-Han Chou et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-30 11:47:16'
tags:
- all search terms
- dataset
theme: light
title: TestTime Consistency in Vision Language Models
---

# title: TestTime Consistency in Vision Language Models 
## publish date: 
**2025-06-27** 
## authors: 
  Shih-Han Chou et.al. 
## paper id
2506.22395v1
## download
[2506.22395v1](http://arxiv.org/abs/2506.22395v1)
## abstracts:
Vision-Language Models (VLMs) have achieved impressive performance across a wide range of multimodal tasks, yet they often exhibit inconsistent behavior when faced with semantically equivalent inputs, undermining their reliability and robustness. Recent benchmarks, such as MM-R3, highlight that even state-of-the-art VLMs can produce divergent predictions across semantically equivalent inputs, despite maintaining high average accuracy. Prior work addresses this issue by modifying model architectures or conducting large-scale fine-tuning on curated datasets. In contrast, we propose a simple and effective test-time consistency framework that enhances semantic consistency without supervised re-training. Our method is entirely post-hoc, model-agnostic, and applicable to any VLM with access to its weights. Given a single test point, we enforce consistent predictions via two complementary objectives: (i) a Cross-Entropy Agreement Loss that aligns predictive distributions across semantically equivalent inputs, and (ii) a Pseudo-Label Consistency Loss that draws outputs toward a self-averaged consensus. Our method is plug-and-play and leverages information from a single test input itself to improve consistency. Experiments on the MM-R3 benchmark show that our framework yields substantial gains in consistency across state-of-the-art models, establishing a new direction for inference-time adaptation in multimodal learning.
## QA:
coming soon
