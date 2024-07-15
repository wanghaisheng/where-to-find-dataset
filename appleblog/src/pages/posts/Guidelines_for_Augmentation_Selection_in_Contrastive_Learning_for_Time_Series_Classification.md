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
- content: Ziyu Liu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-15 11:33:20'
tags:
- all search terms
- dataset
theme: light
title: Guidelines for Augmentation Selection in Contrastive Learning for Time Series
  Classification
---

# title: Guidelines for Augmentation Selection in Contrastive Learning for Time Series Classification 
## publish date: 
**2024-07-12** 
## authors: 
  Ziyu Liu et.al. 
## paper id
2407.09336v1
## download
[2407.09336v1](http://arxiv.org/abs/2407.09336v1)
## abstracts:
Self-supervised contrastive learning has become a key technique in deep learning, particularly in time series analysis, due to its ability to learn meaningful representations without explicit supervision. Augmentation is a critical component in contrastive learning, where different augmentations can dramatically impact performance, sometimes influencing accuracy by over 30%. However, the selection of augmentations is predominantly empirical which can be suboptimal, or grid searching that is time-consuming. In this paper, we establish a principled framework for selecting augmentations based on dataset characteristics such as trend and seasonality. Specifically, we construct 12 synthetic datasets incorporating trend, seasonality, and integration weights. We then evaluate the effectiveness of 8 different augmentations across these synthetic datasets, thereby inducing generalizable associations between time series characteristics and augmentation efficiency. Additionally, we evaluated the induced associations across 6 real-world datasets encompassing domains such as activity recognition, disease diagnosis, traffic monitoring, electricity usage, mechanical fault prognosis, and finance. These real-world datasets are diverse, covering a range from 1 to 12 channels, 2 to 10 classes, sequence lengths of 14 to 1280, and data frequencies from 250 Hz to daily intervals. The experimental results show that our proposed trend-seasonality-based augmentation recommendation algorithm can accurately identify the effective augmentations for a given time series dataset, achieving an average Recall@3 of 0.667, outperforming baselines. Our work provides guidance for studies employing contrastive learning in time series analysis, with wide-ranging applications. All the code, datasets, and analysis results will be released at https://github.com/DL4mHealth/TS-Contrastive-Augmentation-Recommendation.
## QA:
coming soon
