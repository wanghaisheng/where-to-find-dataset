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
- content: Yajie Bao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-22 11:32:52'
tags:
- all search terms
- dataset on github
theme: light
title: Adaptive Uncertainty Quantification for Scenariobased Control Using Metalearning
  of Bayesian Neural Networks
---

# title: Adaptive Uncertainty Quantification for Scenariobased Control Using Metalearning of Bayesian Neural Networks 
## publish date: 
**2024-07-19** 
## authors: 
  Yajie Bao et.al. 
## paper id
2407.14492v1
## download
[2407.14492v1](http://arxiv.org/abs/2407.14492v1)
## abstracts:
Scenario-based optimization and control has proven to be an efficient approach to account for system uncertainty. In particular, the performance of scenario-based model predictive control (MPC) schemes depends on the accuracy of uncertainty quantification. However, current learning- and scenario-based MPC (sMPC) approaches employ a single timeinvariant probabilistic model (learned offline), which may not accurately describe time-varying uncertainties. Instead, this paper presents a model-agnostic meta-learning (MAML) of Bayesian neural networks (BNN) for adaptive uncertainty quantification that would be subsequently used for adaptive-scenario-tree model predictive control design of nonlinear systems with unknown dynamics to enhance control performance. In particular, the proposed approach learns both a global BNN model and an updating law to refine the BNN model. At each time step, the updating law transforms the global BNN model into more precise local BNN models in real time. The adapted local model is then used to generate scenarios for sMPC design at each time step. A probabilistic safety certificate is incorporated in the scenario generation to ensure that the trajectories of the generated scenarios contain the real trajectory of the system and that all the scenarios adhere to the constraints with a high probability. Experiments using closed-loop simulations of a numerical example demonstrate that the proposed approach can improve the performance of scenario-based MPC compared to using only one BNN model learned offline for all time steps.
## QA:
coming soon
