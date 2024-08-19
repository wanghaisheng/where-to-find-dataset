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
- content: Dingwei Chen et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-19 11:32:23'
tags:
- all search terms
- dataset
theme: light
title: Lower Layer Matters Alleviating Hallucination via MultiLayer Fusion Contrastive
  Decoding with Truthfulness Refocused
---

# title: Lower Layer Matters Alleviating Hallucination via MultiLayer Fusion Contrastive Decoding with Truthfulness Refocused 
## publish date: 
**2024-08-16** 
## authors: 
  Dingwei Chen et.al. 
## paper id
2408.08769v1
## download
[2408.08769v1](http://arxiv.org/abs/2408.08769v1)
## abstracts:
Large Language Models (LLMs) have demonstrated exceptional performance across various natural language processing tasks, yet they occasionally tend to yield content that factually inaccurate or discordant with the expected output, a phenomenon empirically referred to as "hallucination". To tackle this issue, recent works have investigated contrastive decoding between the original model and an amateur model with induced hallucination, which has shown promising results. Nonetheless, this method may undermine the output distribution of the original LLM caused by its coarse contrast and simplistic subtraction operation, potentially leading to errors in certain cases. In this paper, we introduce a novel contrastive decoding framework termed LOL (LOwer Layer Matters). Our approach involves concatenating the contrastive decoding of both the final and lower layers between the original model and the amateur model, thereby achieving multi-layer fusion to aid in the mitigation of hallucination. Additionally, we incorporate a truthfulness refocused module that leverages contextual guidance to enhance factual encoding, further capturing truthfulness during contrastive decoding. Extensive experiments conducted on two publicly available datasets illustrate that our proposed LOL framework can substantially alleviate hallucination while surpassing existing baselines in most cases. Compared with the best baseline, we improve by average 4.5 points on all metrics of TruthfulQA. The source code is coming soon.
## QA:
coming soon
