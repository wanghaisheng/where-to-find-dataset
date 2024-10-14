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
- content: Zichao Yu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-14 11:37:28'
tags:
- all search terms
- dataset
theme: light
title: DataDriven Neural Estimation of Indirect RateDistortion Function
---

# title: DataDriven Neural Estimation of Indirect RateDistortion Function 
## publish date: 
**2024-10-11** 
## authors: 
  Zichao Yu et.al. 
## paper id
2410.09018v1
## download
[2410.09018v1](http://arxiv.org/abs/2410.09018v1)
## abstracts:
The rate-distortion function (RDF) has long been an information-theoretic benchmark for data compression. As its natural extension, the indirect rate-distortion function (iRDF) corresponds to the scenario where the encoder can only access an observation correlated with the source, rather than the source itself. Such scenario is also relevant for modern applications like remote sensing and goal-oriented communication. The iRDF can be reduced into a standard RDF with the distortion measure replaced by its conditional expectation conditioned upon the observation. This reduction, however, leads to a non-trivial challenge when one needs to estimate the iRDF given datasets only, because without statistical knowledge of the joint probability distribution between the source and its observation, the conditional expectation cannot be evaluated. To tackle this challenge, starting from the well known fact that conditional expectation is the minimum mean-squared error estimator and exploiting a Markovian relationship, we identify a functional equivalence between the reduced distortion measure in the iRDF and the solution of a quadratic loss minimization problem, which can be efficiently approximated by neural network approach. We proceed to reformulate the iRDF as a variational problem corresponding to the Lagrangian representation of the iRDF curve, and propose a neural network based approximate solution, integrating the aforementioned distortion measure estimator. Asymptotic analysis guarantees consistency of the solution, and numerical experimental results demonstrate the accuracy and effectiveness of the algorithm.
## QA:
coming soon
