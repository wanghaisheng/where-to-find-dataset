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
- content: Yohan Poirier-Ginter et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-16 11:36:08'
tags:
- dataset
- all search terms
theme: light
title: A Diffusion Approach to Radiance Field Relighting using MultiIllumination Synthesis
---

# title: A Diffusion Approach to Radiance Field Relighting using MultiIllumination Synthesis 
## publish date: 
**2024-09-13** 
## authors: 
  Yohan Poirier-Ginter et.al. 
## paper id
2409.08947v1
## download
[2409.08947v1](http://arxiv.org/abs/2409.08947v1)
## abstracts:
Relighting radiance fields is severely underconstrained for multi-view data, which is most often captured under a single illumination condition; It is especially hard for full scenes containing multiple objects. We introduce a method to create relightable radiance fields using such single-illumination data by exploiting priors extracted from 2D image diffusion models. We first fine-tune a 2D diffusion model on a multi-illumination dataset conditioned by light direction, allowing us to augment a single-illumination capture into a realistic -- but possibly inconsistent -- multi-illumination dataset from directly defined light directions. We use this augmented data to create a relightable radiance field represented by 3D Gaussian splats. To allow direct control of light direction for low-frequency lighting, we represent appearance with a multi-layer perceptron parameterized on light direction. To enforce multi-view consistency and overcome inaccuracies we optimize a per-image auxiliary feature vector. We show results on synthetic and real multi-view data under single illumination, demonstrating that our method successfully exploits 2D diffusion model priors to allow realistic 3D relighting for complete scenes. Project site https://repo-sam.inria.fr/fungraph/generative-radiance-field-relighting/
## QA:
coming soon
