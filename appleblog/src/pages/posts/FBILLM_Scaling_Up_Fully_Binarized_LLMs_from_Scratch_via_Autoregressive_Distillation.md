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
- content: Liqun Ma et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-10 12:47:25'
tags:
- dataset
- all search terms
theme: light
title: FBILLM Scaling Up Fully Binarized LLMs from Scratch via Autoregressive Distillation
---

# title: FBILLM Scaling Up Fully Binarized LLMs from Scratch via Autoregressive Distillation 
## publish date: 
**2024-07-09** 
## authors: 
  Liqun Ma et.al. 
## paper id
2407.07093v1
## download
[2407.07093v1](http://arxiv.org/abs/2407.07093v1)
## abstracts:
This work presents a Fully BInarized Large Language Model (FBI-LLM), demonstrating for the first time how to train a large-scale binary language model from scratch (not the partial binary or ternary LLM like BitNet b1.58) to match the performance of its full-precision counterparts (e.g., FP16 or BF16) in transformer-based LLMs. It achieves this by employing an autoregressive distillation (AD) loss with maintaining equivalent model dimensions (130M, 1.3B, 7B) and training data volume as regular LLM pretraining, while delivering competitive results in terms of perplexity and task-specific effectiveness. Intriguingly, by analyzing the training trajectory, we find that the pretrained weight is not necessary for training binarized LLMs from scratch. This research encourages a new computational framework and may facilitate the future design of specialized hardware tailored for fully 1-bit LLMs. We make all models, code, and training dataset fully accessible and transparent to support further research (Code: https://github.com/LiqunMa/FBI-LLM. Model: https://huggingface.co/LiqunMa/).
## QA:
coming soon
