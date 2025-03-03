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
- content: Qingsen Yan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-03 11:38:19'
tags:
- dataset
- all search terms
theme: light
title: HVI A New Color Space for Lowlight Image Enhancement
---

# title: HVI A New Color Space for Lowlight Image Enhancement 
## publish date: 
**2025-02-27** 
## authors: 
  Qingsen Yan et.al. 
## paper id
2502.20272v2
## download
[2502.20272v2](http://arxiv.org/abs/2502.20272v2)
## abstracts:
Low-Light Image Enhancement (LLIE) is a crucial computer vision task that aims to restore detailed visual information from corrupted low-light images. Many existing LLIE methods are based on standard RGB (sRGB) space, which often produce color bias and brightness artifacts due to inherent high color sensitivity in sRGB. While converting the images using Hue, Saturation and Value (HSV) color space helps resolve the brightness issue, it introduces significant red and black noise artifacts. To address this issue, we propose a new color space for LLIE, namely Horizontal/Vertical-Intensity (HVI), defined by polarized HS maps and learnable intensity. The former enforces small distances for red coordinates to remove the red artifacts, while the latter compresses the low-light regions to remove the black artifacts. To fully leverage the chromatic and intensity information, a novel Color and Intensity Decoupling Network (CIDNet) is further introduced to learn accurate photometric mapping function under different lighting conditions in the HVI space. Comprehensive results from benchmark and ablation experiments show that the proposed HVI color space with CIDNet outperforms the state-of-the-art methods on 10 datasets. The code is available at https://github.com/Fediory/HVI-CIDNet.
## QA:
coming soon
