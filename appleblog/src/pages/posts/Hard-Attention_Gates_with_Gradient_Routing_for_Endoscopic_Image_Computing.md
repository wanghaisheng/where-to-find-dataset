---
layout: '../../layouts/MarkdownPost.astro'
title: '**Hard-Attention Gates with Gradient Routing for Endoscopic Image Computing**'
pubDate: '2024-07-09 06:48:35'
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
   content: Giorgio Roffo et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04400v1
## download
[2407.04400v1](http://arxiv.org/abs/2407.04400v1)
## abstracts:
To address overfitting and enhance model generalization in gastroenterological polyp size assessment, our study introduces Feature-Selection Gates (FSG) or Hard-Attention Gates (HAG) alongside Gradient Routing (GR) for dynamic feature selection. This technique aims to boost Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) by promoting sparse connectivity, thereby reducing overfitting and enhancing generalization. HAG achieves this through sparsification with learnable weights, serving as a regularization strategy. GR further refines this process by optimizing HAG parameters via dual forward passes, independently from the main model, to improve feature re-weighting. Our evaluation spanned multiple datasets, including CIFAR-100 for a broad impact assessment and specialized endoscopic datasets (REAL-Colon, Misawa, and SUN) focusing on polyp size estimation, covering over 200 polyps in more than 370,000 frames. The findings indicate that our HAG-enhanced networks substantially enhance performance in both binary and triclass classification tasks related to polyp sizing. Specifically, CNNs experienced an F1 Score improvement to 87.8% in binary classification, while in triclass classification, the ViT-T model reached an F1 Score of 76.5%, outperforming traditional CNNs and ViT-T models. To facilitate further research, we are releasing our codebase, which includes implementations for CNNs, multistream CNNs, ViT, and HAG-augmented variants. This resource aims to standardize the use of endoscopic datasets, providing public training-validation-testing splits for reliable and comparable research in gastroenterological polyp size estimation. The codebase is available at github.com/cosmoimd/feature-selection-gates.
## QA:
coming soon
