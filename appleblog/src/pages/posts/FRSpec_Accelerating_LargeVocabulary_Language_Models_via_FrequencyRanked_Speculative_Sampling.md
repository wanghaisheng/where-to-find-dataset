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
- content: Weilin Zhao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-24 11:36:34'
tags:
- dataset
- all search terms
theme: light
title: FRSpec Accelerating LargeVocabulary Language Models via FrequencyRanked Speculative
  Sampling
---

# title: FRSpec Accelerating LargeVocabulary Language Models via FrequencyRanked Speculative Sampling 
## publish date: 
**2025-02-20** 
## authors: 
  Weilin Zhao et.al. 
## paper id
2502.14856v1
## download
[2502.14856v1](http://arxiv.org/abs/2502.14856v1)
## abstracts:
Speculative sampling has emerged as an important technique for accelerating the auto-regressive generation process of large language models (LLMs) by utilizing a draft-then-verify mechanism to produce multiple tokens per forward pass. While state-of-the-art speculative sampling methods use only a single layer and a language modeling (LM) head as the draft model to achieve impressive layer compression, their efficiency gains are substantially reduced for large-vocabulary LLMs, such as Llama-3-8B with a vocabulary of 128k tokens. To address this, we present FR-Spec, a frequency-ranked speculative sampling framework that optimizes draft candidate selection through vocabulary space compression. By constraining the draft search to a frequency-prioritized token subset, our method reduces LM Head computation overhead by 75% while ensuring the equivalence of the final output distribution. Experiments across multiple datasets demonstrate an average of 1.12$\times$ speedup over the state-of-the-art speculative sampling method EAGLE-2.
## QA:
coming soon
