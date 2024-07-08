---
layout: '../../layouts/MarkdownPost.astro'
title: '**Simulation-based Calibration of Uncertainty Intervals under Approximate Bayesian Estimation**'
pubDate: '2024-07-09 06:54:42'
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: '['dataset', 'all search terms']' 
theme: 'light'
featured: true

meta:
 - name: author
   content: Terrance D. Savitsky et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04659v1
## download
[2407.04659v1](http://arxiv.org/abs/2407.04659v1)
## abstracts:
The mean field variational Bayes (VB) algorithm implemented in Stan is relatively fast and efficient, making it feasible to produce model-estimated official statistics on a rapid timeline. Yet, while consistent point estimates of parameters are achieved for continuous data models, the mean field approximation often produces inaccurate uncertainty quantification to the extent that parameters are correlated a posteriori. In this paper, we propose a simulation procedure that calibrates uncertainty intervals for model parameters estimated under approximate algorithms to achieve nominal coverages. Our procedure detects and corrects biased estimation of both first and second moments of approximate marginal posterior distributions induced by any estimation algorithm that produces consistent first moments under specification of the correct model. The method generates replicate datasets using parameters estimated in an initial model run. The model is subsequently re-estimated on each replicate dataset, and we use the empirical distribution over the re-samples to formulate calibrated confidence intervals of parameter estimates of the initial model run that are guaranteed to asymptotically achieve nominal coverage. We demonstrate the performance of our procedure in Monte Carlo simulation study and apply it to real data from the Current Employment Statistics survey.
## QA:
coming soon
