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
- content: Roman Hornung et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-16 11:36:10'
tags:
- dataset
- all search terms
theme: light
title: Multi forests Variable importance for multiclass outcomes
---

# title: Multi forests Variable importance for multiclass outcomes 
## publish date: 
**2024-09-13** 
## authors: 
  Roman Hornung et.al. 
## paper id
2409.08925v1
## download
[2409.08925v1](http://arxiv.org/abs/2409.08925v1)
## abstracts:
In prediction tasks with multi-class outcomes, identifying covariates specifically associated with one or more outcome classes can be important. Conventional variable importance measures (VIMs) from random forests (RFs), like permutation and Gini importance, focus on overall predictive performance or node purity, without differentiating between the classes. Therefore, they can be expected to fail to distinguish class-associated covariates from covariates that only distinguish between groups of classes. We introduce a VIM called multi-class VIM, tailored for identifying exclusively class-associated covariates, via a novel RF variant called multi forests (MuFs). The trees in MuFs use both multi-way and binary splitting. The multi-way splits generate child nodes for each class, using a split criterion that evaluates how well these nodes represent their respective classes. This setup forms the basis of the multi-class VIM, which measures the discriminatory ability of the splits performed in the respective covariates with regard to this split criterion. Alongside the multi-class VIM, we introduce a second VIM, the discriminatory VIM. This measure, based on the binary splits, assesses the strength of the general influence of the covariates, irrespective of their class-associatedness. Simulation studies demonstrate that the multi-class VIM specifically ranks class-associated covariates highly, unlike conventional VIMs which also rank other types of covariates highly. Analyses of 121 datasets reveal that MuFs often have slightly lower predictive performance compared to conventional RFs. This is, however, not a limiting factor given the algorithm's primary purpose of calculating the multi-class VIM.
## QA:
coming soon
