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
- content: Xiaobei Zhao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-10 11:31:51'
tags:
- dataset
- all search terms
theme: light
title: TomatoScanner phenotyping tomato fruit based on only RGB image
---

# title: TomatoScanner phenotyping tomato fruit based on only RGB image 
## publish date: 
**2025-03-07** 
## authors: 
  Xiaobei Zhao et.al. 
## paper id
2503.05568v1
## download
[2503.05568v1](http://arxiv.org/abs/2503.05568v1)
## abstracts:
In tomato greenhouse, phenotypic measurement is meaningful for researchers and farmers to monitor crop growth, thereby precisely control environmental conditions in time, leading to better quality and higher yield. Traditional phenotyping mainly relies on manual measurement, which is accurate but inefficient, more importantly, endangering the health and safety of people. Several studies have explored computer vision-based methods to replace manual phenotyping. However, the 2D-based need extra calibration, or cause destruction to fruit, or can only measure limited and meaningless traits. The 3D-based need extra depth camera, which is expensive and unacceptable for most farmers. In this paper, we propose a non-contact tomato fruit phenotyping method, titled TomatoScanner, where RGB image is all you need for input. First, pixel feature is extracted by instance segmentation of our proposed EdgeYOLO with preprocessing of individual separation and pose correction. Second, depth feature is extracted by depth estimation of Depth Pro. Third, pixel and depth feature are fused to output phenotype results in reality. We establish self-built Tomato Phenotype Dataset to test TomatoScanner, which achieves excellent phenotyping on width, height, vertical area and volume, with median relative error of 5.63%, 7.03%, -0.64% and 37.06%, respectively. We propose and add three innovative modules - EdgeAttention, EdgeLoss and EdgeBoost - into EdgeYOLO, to enhance the segmentation accuracy on edge portion. Precision and mean Edge Error greatly improve from 0.943 and 5.641% to 0.986 and 2.963%, respectively. Meanwhile, EdgeYOLO keeps lightweight and efficient, with 48.7 M weights size and 76.34 FPS. Codes and datasets: https://github.com/AlexTraveling/TomatoScanner.
## QA:
coming soon
