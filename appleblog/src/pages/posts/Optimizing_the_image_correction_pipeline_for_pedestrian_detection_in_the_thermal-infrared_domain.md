---
layout: '../../layouts/MarkdownPost.astro'
title: '**Optimizing the image correction pipeline for pedestrian detection in the thermal-infrared domain**'
pubDate: '2024-07-09 06:48:34'
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
   content: Christophe Karam et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04484v1
## download
[2407.04484v1](http://arxiv.org/abs/2407.04484v1)
## abstracts:
Infrared imagery can help in low-visibility situations such as fog and low-light scenarios, but it is prone to thermal noise and requires further processing and correction. This work studies the effect of different infrared processing pipelines on the performance of a pedestrian detection in an urban environment, similar to autonomous driving scenarios. Detection on infrared images is shown to outperform that on visible images, but the infrared correction pipeline is crucial since the models cannot extract information from raw infrared images. Two thermal correction pipelines are studied, the shutter and the shutterless pipes. Experiments show that some correction algorithms like spatial denoising are detrimental to performance even if they increase visual quality for a human observer. Other algorithms like destriping and, to a lesser extent, temporal denoising, increase computational time, but have some role to play in increasing detection accuracy. As it stands, the optimal trade-off for speed and accuracy is simply to use the shutterless pipe with a tonemapping algorithm only, for autonomous driving applications within varied environments.
## QA:
coming soon
