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
- content: Chenshu Hou et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-22 11:32:52'
tags:
- all search terms
- dataset on github
theme: light
title: PDTPE Parallel Decoder with Textguided Position Encoding for 3D Visual Grounding
---

# title: PDTPE Parallel Decoder with Textguided Position Encoding for 3D Visual Grounding 
## publish date: 
**2024-07-19** 
## authors: 
  Chenshu Hou et.al. 
## paper id
2407.14491v1
## download
[2407.14491v1](http://arxiv.org/abs/2407.14491v1)
## abstracts:
3D visual grounding aims to locate the target object mentioned by free-formed natural language descriptions in 3D point cloud scenes. Most previous work requires the encoder-decoder to simultaneously align the attribute information of the target object and its relational information with the surrounding environment across modalities. This causes the queries' attention to be dispersed, potentially leading to an excessive focus on points irrelevant to the input language descriptions. To alleviate these issues, we propose PD-TPE, a visual-language model with a double-branch decoder. The two branches perform proposal feature decoding and surrounding layout awareness in parallel. Since their attention maps are not influenced by each other, the queries focus on tokens relevant to each branch's specific objective. In particular, we design a novel Text-guided Position Encoding method, which differs between the two branches. In the main branch, the priori relies on the relative positions between tokens and predicted 3D boxes, which direct the model to pay more attention to tokens near the object; in the surrounding branch, it is guided by the similarity between visual and text features, so that the queries attend to tokens that can provide effective layout information. Extensive experiments demonstrate that we surpass the state-of-the-art on two widely adopted 3D visual grounding datasets, ScanRefer and NR3D, by 1.8% and 2.2%, respectively. Codes will be made publicly available.
## QA:
coming soon
