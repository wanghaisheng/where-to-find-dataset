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
- content: Thomas Kwa et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-22 11:32:49'
tags:
- all search terms
- dataset on github
theme: light
title: Catastrophic Goodhart regularizing RLHF with KL divergence does not mitigate
  heavytailed reward misspecification
---

# title: Catastrophic Goodhart regularizing RLHF with KL divergence does not mitigate heavytailed reward misspecification 
## publish date: 
**2024-07-19** 
## authors: 
  Thomas Kwa et.al. 
## paper id
2407.14503v1
## download
[2407.14503v1](http://arxiv.org/abs/2407.14503v1)
## abstracts:
When applying reinforcement learning from human feedback (RLHF), the reward is learned from data and, therefore, always has some error. It is common to mitigate this by regularizing the policy with KL divergence from a base model, with the hope that balancing reward with regularization will achieve desirable outcomes despite this reward misspecification. We show that when the reward function has light-tailed error, optimal policies under less restrictive KL penalties achieve arbitrarily high utility. However, if error is heavy-tailed, some policies obtain arbitrarily high reward despite achieving no more utility than the base model--a phenomenon we call catastrophic Goodhart. We adapt a discrete optimization method to measure the tails of reward models, finding that they are consistent with light-tailed error. However, the pervasiveness of heavy-tailed distributions in many real-world applications indicates that future sources of RL reward could have heavy-tailed error, increasing the likelihood of reward hacking even with KL regularization.
## QA:
coming soon
