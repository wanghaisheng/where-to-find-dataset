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
- content: Joseph Geo Benjamin et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-02 01:35:16'
tags:
- all search terms
- dataset
theme: light
title: Leveraging SelfSupervised Learning for Fetal Cardiac Planes Classification
  using Ultrasound Scan Videos
---

# title: Leveraging SelfSupervised Learning for Fetal Cardiac Planes Classification using Ultrasound Scan Videos 
## publish date: 
**2024-07-31** 
## authors: 
  Joseph Geo Benjamin et.al. 
## paper id
2407.21738v1
## download
[2407.21738v1](http://arxiv.org/abs/2407.21738v1)
## abstracts:
Self-supervised learning (SSL) methods are popular since they can address situations with limited annotated data by directly utilising the underlying data distribution. However, the adoption of such methods is not explored enough in ultrasound (US) imaging, especially for fetal assessment. We investigate the potential of dual-encoder SSL in utilizing unlabelled US video data to improve the performance of challenging downstream Standard Fetal Cardiac Planes (SFCP) classification using limited labelled 2D US images. We study 7 SSL approaches based on reconstruction, contrastive loss, distillation, and information theory and evaluate them extensively on a large private US dataset. Our observations and findings are consolidated from more than 500 downstream training experiments under different settings. Our primary observation shows that for SSL training, the variance of the dataset is more crucial than its size because it allows the model to learn generalisable representations, which improve the performance of downstream tasks. Overall, the BarlowTwins method shows robust performance, irrespective of the training settings and data variations, when used as an initialisation for downstream tasks. Notably, full fine-tuning with 1% of labelled data outperforms ImageNet initialisation by 12% in F1-score and outperforms other SSL initialisations by at least 4% in F1-score, thus making it a promising candidate for transfer learning from US video to image data.
## QA:
coming soon
