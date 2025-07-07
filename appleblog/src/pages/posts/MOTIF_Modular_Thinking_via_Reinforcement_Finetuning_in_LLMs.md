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
- content: Purbesh Mitra et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-07-07 12:06:02'
tags:
- dataset
- all search terms
theme: light
title: MOTIF Modular Thinking via Reinforcement Finetuning in LLMs
---

# title: MOTIF Modular Thinking via Reinforcement Finetuning in LLMs 
## publish date: 
**2025-07-03** 
## authors: 
  Purbesh Mitra et.al. 
## paper id
2507.02851v1
## download
[2507.02851v1](http://arxiv.org/abs/2507.02851v1)
## abstracts:
Recent advancements in the reasoning capabilities of large language models (LLMs) show that employing group relative policy optimization (GRPO) algorithm for reinforcement learning (RL) training allows the models to use more thinking/reasoning tokens for generating better responses. However, LLMs can generate only a finite amount of tokens while maintaining attention to the previously generated tokens. This limit, also known as the context size of an LLM, is a bottleneck in LLM reasoning with arbitrarily large number of tokens. To think beyond the limit of context size, an LLM must employ a modular thinking strategy to reason over multiple rounds. In this work, we propose $\textbf{MOTIF: Modular Thinking via Reinforcement Finetuning}$ -- an RL training method for generating thinking tokens in multiple rounds, effectively allowing the model to think with additional context size. We trained the open-source model Qwen2.5-3B-Instruct on GSM8K dataset via parameter efficient fine-tuning and tested its accuracy on MATH500 and AIME2024 benchmarks. Our experiments show 3.8\% and 3.3\% improvements over vanilla GRPO based training in the respective benchmarks. Furthermore, this improvement was achieved with only 15\% of samples, thus demonstrating sample efficiency of MOTIF. Our code and models are available at https://github.com/purbeshmitra/MOTIF and https://huggingface.co/purbeshmitra/MOTIF, respectively.
## QA:
coming soon
