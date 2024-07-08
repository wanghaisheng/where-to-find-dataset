---
layout: '../../layouts/MarkdownPost.astro'
title: '**A spatial-correlated multitask linear mixed-effects model for imaging genetics**'
pubDate: '2024-07-09 06:48:33'
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: '['all search terms', 'Image Classification']' 
theme: 'light'
featured: true

meta:
 - name: author
   content: Zhibin Pu et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04530v1
## download
[2407.04530v1](http://arxiv.org/abs/2407.04530v1)
## abstracts:
Imaging genetics aims to uncover the hidden relationship between imaging quantitative traits (QTs) and genetic markers (e.g. single nucleotide polymorphism (SNP)), and brings valuable insights into the pathogenesis of complex diseases, such as cancers and cognitive disorders (e.g. the Alzheimer's Disease). However, most linear models in imaging genetics didn't explicitly model the inner relationship among QTs, which might miss some potential efficiency gains from information borrowing across brain regions. In this work, we developed a novel Bayesian regression framework for identifying significant associations between QTs and genetic markers while explicitly modeling spatial dependency between QTs, with the main contributions as follows. Firstly, we developed a spatial-correlated multitask linear mixed-effects model (LMM) to account for dependencies between QTs. We incorporated a population-level mixed effects term into the model, taking full advantage of the dependent structure of brain imaging-derived QTs. Secondly, we implemented the model in the Bayesian framework and derived a Markov chain Monte Carlo (MCMC) algorithm to achieve the model inference. Further, we incorporated the MCMC samples with the Cauchy combination test (CCT) to examine the association between SNPs and QTs, which avoided computationally intractable multi-test issues. The simulation studies indicated improved power of our proposed model compared to classic models where inner dependencies of QTs were not modeled. We also applied the new spatial model to an imaging dataset obtained from the Alzheimer's Disease Neuroimaging Initiative (ADNI) database.
## QA:
coming soon
