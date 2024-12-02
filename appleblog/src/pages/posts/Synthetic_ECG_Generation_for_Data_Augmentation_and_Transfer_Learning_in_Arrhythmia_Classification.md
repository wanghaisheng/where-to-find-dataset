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
- content: "Jos\xE9 Fernando N\xFA\xF1ez et.al."
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-02 11:40:44'
tags:
- all search terms
- dataset
theme: light
title: Synthetic ECG Generation for Data Augmentation and Transfer Learning in Arrhythmia
  Classification
---

# title: Synthetic ECG Generation for Data Augmentation and Transfer Learning in Arrhythmia Classification 
## publish date: 
**2024-11-27** 
## authors: 
  José Fernando Núñez et.al. 
## paper id
2411.18456v1
## download
[2411.18456v1](http://arxiv.org/abs/2411.18456v1)
## abstracts:
Deep learning models need a sufficient amount of data in order to be able to find the hidden patterns in it. It is the purpose of generative modeling to learn the data distribution, thus allowing us to sample more data and augment the original dataset. In the context of physiological data, and more specifically electrocardiogram (ECG) data, given its sensitive nature and expensive data collection, we can exploit the benefits of generative models in order to enlarge existing datasets and improve downstream tasks, in our case, classification of heart rhythm.   In this work, we explore the usefulness of synthetic data generated with different generative models from Deep Learning namely Diffweave, Time-Diffusion and Time-VQVAE in order to obtain better classification results for two open source multivariate ECG datasets. Moreover, we also investigate the effects of transfer learning, by fine-tuning a synthetically pre-trained model and then progressively adding increasing proportions of real data. We conclude that although the synthetic samples resemble the real ones, the classification improvement when simply augmenting the real dataset is barely noticeable on individual datasets, but when both datasets are merged the results show an increase across all metrics for the classifiers when using synthetic samples as augmented data. From the fine-tuning results the Time-VQVAE generative model has shown to be superior to the others but not powerful enough to achieve results close to a classifier trained with real data only. In addition, methods and metrics for measuring closeness between synthetic data and the real one have been explored as a side effect of the main research questions of this study.
## QA:
coming soon
