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
- content: Jianyu Zhao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-14 11:37:29'
tags:
- all search terms
- dataset
theme: light
title: CVAMPose Conditional Variational Autoencoder for MultiObject Monocular Pose
  Estimation
---

# title: CVAMPose Conditional Variational Autoencoder for MultiObject Monocular Pose Estimation 
## publish date: 
**2024-10-11** 
## authors: 
  Jianyu Zhao et.al. 
## paper id
2410.09010v1
## download
[2410.09010v1](http://arxiv.org/abs/2410.09010v1)
## abstracts:
Estimating rigid objects' poses is one of the fundamental problems in computer vision, with a range of applications across automation and augmented reality. Most existing approaches adopt one network per object class strategy, depend heavily on objects' 3D models, depth data, and employ a time-consuming iterative refinement, which could be impractical for some applications. This paper presents a novel approach, CVAM-Pose, for multi-object monocular pose estimation that addresses these limitations. The CVAM-Pose method employs a label-embedded conditional variational autoencoder network, to implicitly abstract regularised representations of multiple objects in a single low-dimensional latent space. This autoencoding process uses only images captured by a projective camera and is robust to objects' occlusion and scene clutter. The classes of objects are one-hot encoded and embedded throughout the network. The proposed label-embedded pose regression strategy interprets the learnt latent space representations utilising continuous pose representations. Ablation tests and systematic evaluations demonstrate the scalability and efficiency of the CVAM-Pose method for multi-object scenarios. The proposed CVAM-Pose outperforms competing latent space approaches. For example, it is respectively 25% and 20% better than AAE and Multi-Path methods, when evaluated using the $\mathrm{AR_{VSD}}$ metric on the Linemod-Occluded dataset. It also achieves results somewhat comparable to methods reliant on 3D models reported in BOP challenges. Code available: https://github.com/JZhao12/CVAM-Pose
## QA:
coming soon
