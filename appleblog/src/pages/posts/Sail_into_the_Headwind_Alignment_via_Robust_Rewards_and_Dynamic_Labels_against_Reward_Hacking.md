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
- content: Paria Rashidinejad et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-16 11:41:09'
tags:
- all search terms
- dataset
theme: light
title: Sail into the Headwind Alignment via Robust Rewards and Dynamic Labels against
  Reward Hacking
---

# title: Sail into the Headwind Alignment via Robust Rewards and Dynamic Labels against Reward Hacking 
## publish date: 
**2024-12-12** 
## authors: 
  Paria Rashidinejad et.al. 
## paper id
2412.09544v1
## download
[2412.09544v1](http://arxiv.org/abs/2412.09544v1)
## abstracts:
Aligning AI systems with human preferences typically suffers from the infamous reward hacking problem, where optimization of an imperfect reward model leads to undesired behaviors. In this paper, we investigate reward hacking in offline preference optimization, which aims to improve an initial model using a preference dataset. We identify two types of reward hacking stemming from statistical fluctuations in the dataset: Type I Reward Hacking due to subpar choices appearing more favorable, and Type II Reward Hacking due to decent choices appearing less favorable. We prove that many (mainstream or theoretical) preference optimization methods suffer from both types of reward hacking. To mitigate Type I Reward Hacking, we propose POWER, a new preference optimization method that combines Guiasu's weighted entropy with a robust reward maximization objective. POWER enjoys finite-sample guarantees under general function approximation, competing with the best covered policy in the data. To mitigate Type II Reward Hacking, we analyze the learning dynamics of preference optimization and develop a novel technique that dynamically updates preference labels toward certain "stationary labels", resulting in diminishing gradients for untrustworthy samples. Empirically, POWER with dynamic labels (POWER-DL) consistently outperforms state-of-the-art methods on alignment benchmarks, achieving improvements of up to 13.0 points on AlpacaEval 2.0 and 11.5 points on Arena-Hard over DPO, while also improving or maintaining performance on downstream tasks such as mathematical reasoning. Strong theoretical guarantees and empirical results demonstrate the promise of POWER-DL in mitigating reward hacking.
## QA:
coming soon
