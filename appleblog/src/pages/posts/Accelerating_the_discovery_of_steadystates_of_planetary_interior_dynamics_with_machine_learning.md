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
- content: Siddhant Agarwal et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-02 11:33:07'
tags:
- dataset
- all search terms
theme: light
title: Accelerating the discovery of steadystates of planetary interior dynamics with
  machine learning
---

# title: Accelerating the discovery of steadystates of planetary interior dynamics with machine learning 
## publish date: 
**2024-08-30** 
## authors: 
  Siddhant Agarwal et.al. 
## paper id
2408.17298v1
## download
[2408.17298v1](http://arxiv.org/abs/2408.17298v1)
## abstracts:
Simulating mantle convection often requires reaching a computationally expensive steady-state, crucial for deriving scaling laws for thermal and dynamical flow properties and benchmarking numerical solutions. The strong temperature dependence of the rheology of mantle rocks causes viscosity variations of several orders of magnitude, leading to a slow-evolving stagnant lid where heat conduction dominates, overlying a rapidly-evolving and strongly convecting region. Time-stepping methods, while effective for fluids with constant viscosity, are hindered by the Courant criterion, which restricts the time step based on the system's maximum velocity and grid size. Consequently, achieving steady-state requires a large number of time steps due to the disparate time scales governing the stagnant and convecting regions.   We present a concept for accelerating mantle convection simulations using machine learning. We generate a dataset of 128 two-dimensional simulations with mixed basal and internal heating, and pressure- and temperature-dependent viscosity. We train a feedforward neural network on 97 simulations to predict steady-state temperature profiles. These can then be used to initialize numerical time stepping methods for different simulation parameters. Compared to typical initializations, the number of time steps required to reach steady-state is reduced by a median factor of 3.75. The benefit of this method lies in requiring very few simulations to train on, providing a solution with no prediction error as we initialize a numerical method, and posing minimal computational overhead at inference time. We demonstrate the effectiveness of our approach and discuss the potential implications for accelerated simulations for advancing mantle convection research.
## QA:
coming soon
