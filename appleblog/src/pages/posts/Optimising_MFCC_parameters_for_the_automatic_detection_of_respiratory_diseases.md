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
- content: Yuyang Yan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-16 08:00:38'
tags:
- all search terms
- dataset
theme: light
title: Optimising MFCC parameters for the automatic detection of respiratory diseases
---

# title: Optimising MFCC parameters for the automatic detection of respiratory diseases 
## publish date: 
**2024-08-14** 
## authors: 
  Yuyang Yan et.al. 
## paper id
2408.07522v1
## download
[2408.07522v1](http://arxiv.org/abs/2408.07522v1)
## abstracts:
Voice signals originating from the respiratory tract are utilized as valuable acoustic biomarkers for the diagnosis and assessment of respiratory diseases. Among the employed acoustic features, Mel Frequency Cepstral Coefficients (MFCC) is widely used for automatic analysis, with MFCC extraction commonly relying on default parameters. However, no comprehensive study has systematically investigated the impact of MFCC extraction parameters on respiratory disease diagnosis. In this study, we address this gap by examining the effects of key parameters, namely the number of coefficients, frame length, and hop length between frames, on respiratory condition examination. Our investigation uses four datasets: the Cambridge COVID-19 Sound database, the Coswara dataset, the Saarbrucken Voice Disorders (SVD) database, and a TACTICAS dataset. The Support Vector Machine (SVM) is employed as the classifier, given its widespread adoption and efficacy. Our findings indicate that the accuracy of MFCC decreases as hop length increases, and the optimal number of coefficients is observed to be approximately 30. The performance of MFCC varies with frame length across the datasets: for the COVID-19 datasets (Cambridge COVID-19 Sound database and Coswara dataset), performance declines with longer frame lengths, while for the SVD dataset, performance improves with increasing frame length (from 50 ms to 500 ms). Furthermore, we investigate the optimized combination of these parameters and observe substantial enhancements in accuracy. Compared to the worst combination, the SVM model achieves an accuracy of 81.1%, 80.6%, and 71.7%, with improvements of 19.6%, 16.10%, and 14.90% for the Cambridge COVID-19 Sound database, the Coswara dataset, and the SVD dataset respectively.
## QA:
coming soon
