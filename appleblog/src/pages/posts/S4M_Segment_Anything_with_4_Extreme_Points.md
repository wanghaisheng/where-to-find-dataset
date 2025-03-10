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
- content: Adrien Meyer et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-10 11:31:52'
tags:
- dataset
- all search terms
theme: light
title: S4M Segment Anything with 4 Extreme Points
---

# title: S4M Segment Anything with 4 Extreme Points 
## publish date: 
**2025-03-07** 
## authors: 
  Adrien Meyer et.al. 
## paper id
2503.05534v1
## download
[2503.05534v1](http://arxiv.org/abs/2503.05534v1)
## abstracts:
The Segment Anything Model (SAM) has revolutionized open-set interactive image segmentation, inspiring numerous adapters for the medical domain. However, SAM primarily relies on sparse prompts such as point or bounding box, which may be suboptimal for fine-grained instance segmentation, particularly in endoscopic imagery, where precise localization is critical and existing prompts struggle to capture object boundaries effectively. To address this, we introduce S4M (Segment Anything with 4 Extreme Points), which augments SAM by leveraging extreme points -- the top-, bottom-, left-, and right-most points of an instance -- prompts. These points are intuitive to identify and provide a faster, structured alternative to box prompts. However, a na\"ive use of extreme points degrades performance, due to SAM's inability to interpret their semantic roles. To resolve this, we introduce dedicated learnable embeddings, enabling the model to distinguish extreme points from generic free-form points and better reason about their spatial relationships. We further propose an auxiliary training task through the Canvas module, which operates solely on prompts -- without vision input -- to predict a coarse instance mask. This encourages the model to internalize the relationship between extreme points and mask distributions, leading to more robust segmentation. S4M outperforms other SAM-based approaches on three endoscopic surgical datasets, demonstrating its effectiveness in complex scenarios. Finally, we validate our approach through a human annotation study on surgical endoscopic videos, confirming that extreme points are faster to acquire than bounding boxes.
## QA:
coming soon
