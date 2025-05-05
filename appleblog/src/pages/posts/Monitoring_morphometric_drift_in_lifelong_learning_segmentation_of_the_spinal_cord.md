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
- content: Enamundram Naga Karthik et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-05 11:43:15'
tags:
- all search terms
- dataset
theme: light
title: Monitoring morphometric drift in lifelong learning segmentation of the spinal
  cord
---

# title: Monitoring morphometric drift in lifelong learning segmentation of the spinal cord 
## publish date: 
**2025-05-02** 
## authors: 
  Enamundram Naga Karthik et.al. 
## paper id
2505.01364v1
## download
[2505.01364v1](http://arxiv.org/abs/2505.01364v1)
## abstracts:
Morphometric measures derived from spinal cord segmentations can serve as diagnostic and prognostic biomarkers in neurological diseases and injuries affecting the spinal cord. While robust, automatic segmentation methods to a wide variety of contrasts and pathologies have been developed over the past few years, whether their predictions are stable as the model is updated using new datasets has not been assessed. This is particularly important for deriving normative values from healthy participants. In this study, we present a spinal cord segmentation model trained on a multisite $(n=75)$ dataset, including 9 different MRI contrasts and several spinal cord pathologies. We also introduce a lifelong learning framework to automatically monitor the morphometric drift as the model is updated using additional datasets. The framework is triggered by an automatic GitHub Actions workflow every time a new model is created, recording the morphometric values derived from the model's predictions over time. As a real-world application of the proposed framework, we employed the spinal cord segmentation model to update a recently-introduced normative database of healthy participants containing commonly used measures of spinal cord morphometry. Results showed that: (i) our model outperforms previous versions and pathology-specific models on challenging lumbar spinal cord cases, achieving an average Dice score of $0.95 \pm 0.03$; (ii) the automatic workflow for monitoring morphometric drift provides a quick feedback loop for developing future segmentation models; and (iii) the scaling factor required to update the database of morphometric measures is nearly constant among slices across the given vertebral levels, showing minimum drift between the current and previous versions of the model monitored by the framework. The model is freely available in Spinal Cord Toolbox v7.0.
## QA:
coming soon
