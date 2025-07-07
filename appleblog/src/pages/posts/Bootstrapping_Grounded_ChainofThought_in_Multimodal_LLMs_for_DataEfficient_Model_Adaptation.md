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
- content: Jiaer Xia et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-07-07 12:06:02'
tags:
- dataset
- all search terms
theme: light
title: Bootstrapping Grounded ChainofThought in Multimodal LLMs for DataEfficient
  Model Adaptation
---

# title: Bootstrapping Grounded ChainofThought in Multimodal LLMs for DataEfficient Model Adaptation 
## publish date: 
**2025-07-03** 
## authors: 
  Jiaer Xia et.al. 
## paper id
2507.02859v1
## download
[2507.02859v1](http://arxiv.org/abs/2507.02859v1)
## abstracts:
Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in interpreting images using natural language. However, without using large-scale datasets for retraining, these models are difficult to adapt to specialized vision tasks, e.g., chart understanding. This problem is caused by a mismatch between pre-training and downstream datasets: pre-training datasets primarily concentrate on scenes and objects but contain limited information about specialized, non-object images, such as charts and tables. In this paper, we share an interesting finding that training an MLLM with Chain-of-Thought (CoT) reasoning data can facilitate model adaptation in specialized vision tasks, especially under data-limited regimes. However, we identify a critical issue within CoT data distilled from pre-trained MLLMs, i.e., the data often contains multiple factual errors in the reasoning steps. To address the problem, we propose Grounded Chain-of-Thought (GCoT), a simple bootstrapping-based approach that aims to inject grounding information (i.e., bounding boxes) into CoT data, essentially making the reasoning steps more faithful to input images. We evaluate our approach on five specialized vision tasks, which cover a variety of visual formats including charts, tables, receipts, and reports. The results demonstrate that under data-limited regimes our approach significantly improves upon fine-tuning and distillation.
## QA:
coming soon
