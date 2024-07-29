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
- content: Shu Ishida et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-29 11:32:39'
tags:
- dataset on github
- all search terms
theme: light
title: SOAPRL Sequential Option Advantage Propagation for Reinforcement Learning in
  POMDP Environments
---

# title: SOAPRL Sequential Option Advantage Propagation for Reinforcement Learning in POMDP Environments 
## publish date: 
**2024-07-26** 
## authors: 
  Shu Ishida et.al. 
## paper id
2407.18913v1
## download
[2407.18913v1](http://arxiv.org/abs/2407.18913v1)
## abstracts:
This work compares ways of extending Reinforcement Learning algorithms to Partially Observed Markov Decision Processes (POMDPs) with options. One view of options is as temporally extended action, which can be realized as a memory that allows the agent to retain historical information beyond the policy's context window. While option assignment could be handled using heuristics and hand-crafted objectives, learning temporally consistent options and associated sub-policies without explicit supervision is a challenge. Two algorithms, PPOEM and SOAP, are proposed and studied in depth to address this problem. PPOEM applies the forward-backward algorithm (for Hidden Markov Models) to optimize the expected returns for an option-augmented policy. However, this learning approach is unstable during on-policy rollouts. It is also unsuited for learning causal policies without the knowledge of future trajectories, since option assignments are optimized for offline sequences where the entire episode is available. As an alternative approach, SOAP evaluates the policy gradient for an optimal option assignment. It extends the concept of the generalized advantage estimation (GAE) to propagate option advantages through time, which is an analytical equivalent to performing temporal back-propagation of option policy gradients. This option policy is only conditional on the history of the agent, not future actions. Evaluated against competing baselines, SOAP exhibited the most robust performance, correctly discovering options for POMDP corridor environments, as well as on standard benchmarks including Atari and MuJoCo, outperforming PPOEM, as well as LSTM and Option-Critic baselines. The open-sourced code is available at https://github.com/shuishida/SoapRL.
## QA:
coming soon
