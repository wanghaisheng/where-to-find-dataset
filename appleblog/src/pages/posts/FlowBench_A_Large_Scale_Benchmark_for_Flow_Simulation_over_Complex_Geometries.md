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
- content: Ronak Tali et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-30 11:37:58'
tags:
- all search terms
- dataset
theme: light
title: FlowBench A Large Scale Benchmark for Flow Simulation over Complex Geometries
---

# title: FlowBench A Large Scale Benchmark for Flow Simulation over Complex Geometries 
## publish date: 
**2024-09-26** 
## authors: 
  Ronak Tali et.al. 
## paper id
2409.18032v1
## download
[2409.18032v1](http://arxiv.org/abs/2409.18032v1)
## abstracts:
Simulating fluid flow around arbitrary shapes is key to solving various engineering problems. However, simulating flow physics across complex geometries remains numerically challenging and computationally resource-intensive, particularly when using conventional PDE solvers. Machine learning methods offer attractive opportunities to create fast and adaptable PDE solvers. However, benchmark datasets to measure the performance of such methods are scarce, especially for flow physics across complex geometries. We introduce FlowBench, a dataset for neural simulators with over 10K samples, which is currently larger than any publicly available flow physics dataset. FlowBench contains flow simulation data across complex geometries (\textit{parametric vs. non-parametric}), spanning a range of flow conditions (\textit{Reynolds number and Grashoff number}), capturing a diverse array of flow phenomena (\textit{steady vs. transient; forced vs. free convection}), and for both 2D and 3D. FlowBench contains over 10K data samples, with each sample the outcome of a fully resolved, direct numerical simulation using a well-validated simulator framework designed for modeling transport phenomena in complex geometries. For each sample, we include velocity, pressure, and temperature field data at 3 different resolutions and several summary statistics features of engineering relevance (such as coefficients of lift and drag, and Nusselt numbers). %Additionally, we include masks and signed distance fields for each shape. We envision that FlowBench will enable evaluating the interplay between complex geometry, coupled flow phenomena, and data sufficiency on the performance of current, and future, neural PDE solvers. We enumerate several evaluation metrics to help rank order the performance of neural PDE solvers. We benchmark the performance of several baseline methods including FNO, CNO, WNO, and DeepONet.
## QA:
coming soon
