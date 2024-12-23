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
- content: Lei Tan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-23 11:35:39'
tags:
- all search terms
- dataset
theme: light
title: Knowing Where to Focus AttentionGuided Alignment for Textbased Person Search
---

# title: Knowing Where to Focus AttentionGuided Alignment for Textbased Person Search 
## publish date: 
**2024-12-19** 
## authors: 
  Lei Tan et.al. 
## paper id
2412.15106v1
## download
[2412.15106v1](http://arxiv.org/abs/2412.15106v1)
## abstracts:
In the realm of Text-Based Person Search (TBPS), mainstream methods aim to explore more efficient interaction frameworks between text descriptions and visual data. However, recent approaches encounter two principal challenges. Firstly, the widely used random-based Masked Language Modeling (MLM) considers all the words in the text equally during training. However, massive semantically vacuous words ('with', 'the', etc.) be masked fail to contribute efficient interaction in the cross-modal MLM and hampers the representation alignment. Secondly, manual descriptions in TBPS datasets are tedious and inevitably contain several inaccuracies. To address these issues, we introduce an Attention-Guided Alignment (AGA) framework featuring two innovative components: Attention-Guided Mask (AGM) Modeling and Text Enrichment Module (TEM). AGM dynamically masks semantically meaningful words by aggregating the attention weight derived from the text encoding process, thereby cross-modal MLM can capture information related to the masked word from text context and images and align their representations. Meanwhile, TEM alleviates low-quality representations caused by repetitive and erroneous text descriptions by replacing those semantically meaningful words with MLM's prediction. It not only enriches text descriptions but also prevents overfitting. Extensive experiments across three challenging benchmarks demonstrate the effectiveness of our AGA, achieving new state-of-the-art results with Rank-1 accuracy reaching 78.36%, 67.31%, and 67.4% on CUHK-PEDES, ICFG-PEDES, and RSTPReid, respectively.
## QA:
coming soon
