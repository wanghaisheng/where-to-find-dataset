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
- content: Cheng Tang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-02 11:40:39'
tags:
- all search terms
- dataset
theme: light
title: Robust Offline Reinforcement Learning with Linearly Structured fDivergence
  Regularization
---

# title: Robust Offline Reinforcement Learning with Linearly Structured fDivergence Regularization 
## publish date: 
**2024-11-27** 
## authors: 
  Cheng Tang et.al. 
## paper id
2411.18612v1
## download
[2411.18612v1](http://arxiv.org/abs/2411.18612v1)
## abstracts:
The Distributionally Robust Markov Decision Process (DRMDP) is a popular framework for addressing dynamics shift in reinforcement learning by learning policies robust to the worst-case transition dynamics within a constrained set. However, solving its dual optimization oracle poses significant challenges, limiting theoretical analysis and computational efficiency. The recently proposed Robust Regularized Markov Decision Process (RRMDP) replaces the uncertainty set constraint with a regularization term on the value function, offering improved scalability and theoretical insights. Yet, existing RRMDP methods rely on unstructured regularization, often leading to overly conservative policies by considering transitions that are unrealistic. To address these issues, we propose a novel framework, the $d$-rectangular linear robust regularized Markov decision process ($d$-RRMDP), which introduces a linear latent structure into both transition kernels and regularization. For the offline RL setting, where an agent learns robust policies from a pre-collected dataset in the nominal environment, we develop a family of algorithms, Robust Regularized Pessimistic Value Iteration (R2PVI), employing linear function approximation and $f$-divergence based regularization terms on transition kernels. We provide instance-dependent upper bounds on the suboptimality gap of R2PVI policies, showing these bounds depend on how well the dataset covers state-action spaces visited by the optimal robust policy under robustly admissible transitions. This term is further shown to be fundamental to $d$-RRMDPs via information-theoretic lower bounds. Finally, numerical experiments validate that R2PVI learns robust policies and is computationally more efficient than methods for constrained DRMDPs.
## QA:
coming soon
