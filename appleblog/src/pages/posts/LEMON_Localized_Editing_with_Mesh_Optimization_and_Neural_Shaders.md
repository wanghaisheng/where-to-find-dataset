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
- content: Furkan Mert Algan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-23 11:35:18'
tags:
- dataset
- all search terms
theme: light
title: LEMON Localized Editing with Mesh Optimization and Neural Shaders
---

# title: LEMON Localized Editing with Mesh Optimization and Neural Shaders 
## publish date: 
**2024-09-18** 
## authors: 
  Furkan Mert Algan et.al. 
## paper id
2409.12024v1
## download
[2409.12024v1](http://arxiv.org/abs/2409.12024v1)
## abstracts:
In practical use cases, polygonal mesh editing can be faster than generating new ones, but it can still be challenging and time-consuming for users. Existing solutions for this problem tend to focus on a single task, either geometry or novel view synthesis, which often leads to disjointed results between the mesh and view. In this work, we propose LEMON, a mesh editing pipeline that combines neural deferred shading with localized mesh optimization. Our approach begins by identifying the most important vertices in the mesh for editing, utilizing a segmentation model to focus on these key regions. Given multi-view images of an object, we optimize a neural shader and a polygonal mesh while extracting the normal map and the rendered image from each view. By using these outputs as conditioning data, we edit the input images with a text-to-image diffusion model and iteratively update our dataset while deforming the mesh. This process results in a polygonal mesh that is edited according to the given text instruction, preserving the geometric characteristics of the initial mesh while focusing on the most significant areas. We evaluate our pipeline using the DTU dataset, demonstrating that it generates finely-edited meshes more rapidly than the current state-of-the-art methods. We include our code and additional results in the supplementary material.
## QA:
coming soon
