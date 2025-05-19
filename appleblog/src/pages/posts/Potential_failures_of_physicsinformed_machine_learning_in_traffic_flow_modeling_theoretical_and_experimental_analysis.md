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
- content: Yuan-Zheng Lei et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-19 11:44:46'
tags:
- dataset on github
- all search terms
theme: light
title: Potential failures of physicsinformed machine learning in traffic flow modeling
  theoretical and experimental analysis
---

# title: Potential failures of physicsinformed machine learning in traffic flow modeling theoretical and experimental analysis 
## publish date: 
**2025-05-16** 
## authors: 
  Yuan-Zheng Lei et.al. 
## paper id
2505.11491v1
## download
[2505.11491v1](http://arxiv.org/abs/2505.11491v1)
## abstracts:
This study critically examines the performance of physics-informed machine learning (PIML) approaches for traffic flow modeling, defining the failure of a PIML model as the scenario where it underperforms both its purely data-driven and purely physics-based counterparts. We analyze the loss landscape by perturbing trained models along the principal eigenvectors of the Hessian matrix and evaluating corresponding loss values. Our results suggest that physics residuals in PIML do not inherently hinder optimization, contrary to a commonly assumed failure cause. Instead, successful parameter updates require both ML and physics gradients to form acute angles with the quasi-true gradient and lie within a conical region. Given inaccuracies in both the physics models and the training data, satisfying this condition is often difficult. Experiments reveal that physical residuals can degrade the performance of LWR- and ARZ-based PIML models, especially under highly physics-driven settings. Moreover, sparse sampling and the use of temporally averaged traffic data can produce misleadingly small physics residuals that fail to capture actual physical dynamics, contributing to model failure. We also identify the Courant-Friedrichs-Lewy (CFL) condition as a key indicator of dataset suitability for PIML, where successful applications consistently adhere to this criterion. Lastly, we observe that higher-order models like ARZ tend to have larger error lower bounds than lower-order models like LWR, which is consistent with the experimental findings of existing studies.
## QA:
coming soon
