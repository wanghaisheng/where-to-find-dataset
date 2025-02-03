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
- content: Ken M. Nakanishi et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-03 11:34:51'
tags:
- all search terms
- dataset on github
theme: light
title: ScalableSoftmax Is Superior for Attention
---

# title: ScalableSoftmax Is Superior for Attention 
## publish date: 
**2025-01-31** 
## authors: 
  Ken M. Nakanishi et.al. 
## paper id
2501.19399v1
## download
[2501.19399v1](http://arxiv.org/abs/2501.19399v1)
## abstracts:
The maximum element of the vector output by the Softmax function approaches zero as the input vector size increases. Transformer-based language models rely on Softmax to compute attention scores, causing the attention distribution to flatten as the context size grows. This reduces the model's ability to prioritize key information effectively and potentially limits its length generalization. To address this problem, we propose Scalable-Softmax (SSMax), which replaces Softmax in scenarios where the input vector size varies. SSMax can be seamlessly integrated into existing Transformer-based architectures. Experimental results in language modeling show that models using SSMax not only achieve faster loss reduction during pretraining but also significantly improve performance in long contexts and key information retrieval. Furthermore, an analysis of attention scores reveals that SSMax enables the model to focus attention on key information even in long contexts. Additionally, although models that use SSMax from the beginning of pretraining achieve better length generalization, those that have already started pretraining can still gain some of this ability by replacing Softmax in the attention layers with SSMax, either during or after pretraining.
## QA:
coming soon
