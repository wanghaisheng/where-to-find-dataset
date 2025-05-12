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
- content: Kunpeng Qiu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-12 11:43:55'
tags:
- dataset
- all search terms
theme: light
title: NoiseConsistent SiameseDiffusion for Medical Image Synthesis and Segmentation
---

# title: NoiseConsistent SiameseDiffusion for Medical Image Synthesis and Segmentation 
## publish date: 
**2025-05-09** 
## authors: 
  Kunpeng Qiu et.al. 
## paper id
2505.06068v1
## download
[2505.06068v1](http://arxiv.org/abs/2505.06068v1)
## abstracts:
Deep learning has revolutionized medical image segmentation, yet its full potential remains constrained by the paucity of annotated datasets. While diffusion models have emerged as a promising approach for generating synthetic image-mask pairs to augment these datasets, they paradoxically suffer from the same data scarcity challenges they aim to mitigate. Traditional mask-only models frequently yield low-fidelity images due to their inability to adequately capture morphological intricacies, which can critically compromise the robustness and reliability of segmentation models. To alleviate this limitation, we introduce Siamese-Diffusion, a novel dual-component model comprising Mask-Diffusion and Image-Diffusion. During training, a Noise Consistency Loss is introduced between these components to enhance the morphological fidelity of Mask-Diffusion in the parameter space. During sampling, only Mask-Diffusion is used, ensuring diversity and scalability. Comprehensive experiments demonstrate the superiority of our method. Siamese-Diffusion boosts SANet's mDice and mIoU by 3.6% and 4.4% on the Polyps, while UNet improves by 1.52% and 1.64% on the ISIC2018. Code is available at GitHub.
## QA:
coming soon
