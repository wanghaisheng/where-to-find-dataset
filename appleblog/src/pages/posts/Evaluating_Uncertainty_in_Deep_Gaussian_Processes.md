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
- content: Matthijs van der Lende et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-04-28 11:42:48'
tags:
- dataset
- all search terms
theme: light
title: Evaluating Uncertainty in Deep Gaussian Processes
---

# title: Evaluating Uncertainty in Deep Gaussian Processes 
## publish date: 
**2025-04-24** 
## authors: 
  Matthijs van der Lende et.al. 
## paper id
2504.17719v1
## download
[2504.17719v1](http://arxiv.org/abs/2504.17719v1)
## abstracts:
Reliable uncertainty estimates are crucial in modern machine learning. Deep Gaussian Processes (DGPs) and Deep Sigma Point Processes (DSPPs) extend GPs hierarchically, offering promising methods for uncertainty quantification grounded in Bayesian principles. However, their empirical calibration and robustness under distribution shift relative to baselines like Deep Ensembles remain understudied. This work evaluates these models on regression (CASP dataset) and classification (ESR dataset) tasks, assessing predictive performance (MAE, Accu- racy), calibration using Negative Log-Likelihood (NLL) and Expected Calibration Error (ECE), alongside robustness under various synthetic feature-level distribution shifts. Results indicate DSPPs provide strong in-distribution calibration leveraging their sigma point approximations. However, compared to Deep Ensembles, which demonstrated superior robustness in both per- formance and calibration under the tested shifts, the GP-based methods showed vulnerabilities, exhibiting particular sensitivity in the observed metrics. Our findings underscore ensembles as a robust baseline, suggesting that while deep GP methods offer good in-distribution calibration, their practical robustness under distribution shift requires careful evaluation. To facilitate reproducibility, we make our code available at https://github.com/matthjs/xai-gp.
## QA:
coming soon
