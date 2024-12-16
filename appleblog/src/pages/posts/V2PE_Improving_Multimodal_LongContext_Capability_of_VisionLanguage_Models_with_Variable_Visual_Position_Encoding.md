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
- content: Junqi Ge et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-16 11:41:05'
tags:
- all search terms
- dataset
theme: light
title: V2PE Improving Multimodal LongContext Capability of VisionLanguage Models with
  Variable Visual Position Encoding
---

# title: V2PE Improving Multimodal LongContext Capability of VisionLanguage Models with Variable Visual Position Encoding 
## publish date: 
**2024-12-12** 
## authors: 
  Junqi Ge et.al. 
## paper id
2412.09616v2
## download
[2412.09616v2](http://arxiv.org/abs/2412.09616v2)
## abstracts:
Vision-Language Models (VLMs) have shown promising capabilities in handling various multimodal tasks, yet they struggle in long-context scenarios, particularly in tasks involving videos, high-resolution images, or lengthy image-text documents. In our work, we first conduct an empirical analysis of the long-context capabilities of VLMs using our augmented long-context multimodal datasets. Our findings reveal that directly applying the positional encoding mechanism used for textual tokens to visual tokens is suboptimal, and VLM performance degrades sharply when the position encoding exceeds the model's context window. To address this, we propose Variable Visual Position Encoding (V2PE), a novel positional encoding approach that employs variable and smaller increments for visual tokens, enabling more efficient management of long multimodal sequences. Our experiments demonstrate the effectiveness of V2PE to enhances VLMs' ability to effectively understand and reason over long multimodal contexts. We further integrate V2PE with our augmented long-context multimodal datasets to fine-tune the open-source VLM, InternVL2. The fine-tuned model achieves strong performance on both standard and long-context multimodal tasks. Notably, when the sequence length of the training dataset is increased to 256K tokens, the model is capable of processing multimodal sequences up to 1M tokens, highlighting its potential for real-world long-context applications.
## QA:
coming soon
