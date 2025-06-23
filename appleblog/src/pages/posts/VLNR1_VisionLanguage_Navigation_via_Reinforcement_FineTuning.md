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
- content: Zhangyang Qi et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-23 11:47:41'
tags:
- all search terms
- dataset
theme: light
title: VLNR1 VisionLanguage Navigation via Reinforcement FineTuning
---

# title: VLNR1 VisionLanguage Navigation via Reinforcement FineTuning 
## publish date: 
**2025-06-20** 
## authors: 
  Zhangyang Qi et.al. 
## paper id
2506.17221v1
## download
[2506.17221v1](http://arxiv.org/abs/2506.17221v1)
## abstracts:
Vision-Language Navigation (VLN) is a core challenge in embodied AI, requiring agents to navigate real-world environments using natural language instructions. Current language model-based navigation systems operate on discrete topological graphs, limiting path planning to predefined node connections. We propose VLN-R1, an end-to-end framework that leverages Large Vision-Language Models (LVLM) to directly translate egocentric video streams into continuous navigation actions, adopting GRPO-based training inspired by DeepSeek-R1. To enable effective training, we first construct the VLN-Ego dataset using a 3D simulator, Habitat, and propose Long-Short Memory Sampling to balance historical and current observations. While large language models can supervise complete textual instructions, they lack fine-grained action-level control. Our framework employs a two-stage training approach: a) Supervised fine-tuning (SFT) to align the model's action sequence text predictions with expert demonstrations, followed by b) Reinforcement fine-tuning (RFT) enhanced with a Time-Decayed Reward (TDR) mechanism that strategically weights multi-step future actions. Experimental results show VLN-R1 achieves strong performance on VLN-CE benchmark. VLN-R1 proves LVLMs can drive embodied navigation and enhance task-specific reasoning through data-efficient, reward-driven post-training.
## QA:
coming soon
