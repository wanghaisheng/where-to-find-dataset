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
- content: Harry Anthony et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-02 11:33:06'
tags:
- dataset
- all search terms
theme: light
title: Evaluating Reliability in Medical DNNs A Critical Analysis of Feature and ConfidenceBased
  OOD Detection
---

# title: Evaluating Reliability in Medical DNNs A Critical Analysis of Feature and ConfidenceBased OOD Detection 
## publish date: 
**2024-08-30** 
## authors: 
  Harry Anthony et.al. 
## paper id
2408.17337v1
## download
[2408.17337v1](http://arxiv.org/abs/2408.17337v1)
## abstracts:
Reliable use of deep neural networks (DNNs) for medical image analysis requires methods to identify inputs that differ significantly from the training data, called out-of-distribution (OOD), to prevent erroneous predictions. OOD detection methods can be categorised as either confidence-based (using the model's output layer for OOD detection) or feature-based (not using the output layer). We created two new OOD benchmarks by dividing the D7P (dermatology) and BreastMNIST (ultrasound) datasets into subsets which either contain or don't contain an artefact (rulers or annotations respectively). Models were trained with artefact-free images, and images with the artefacts were used as OOD test sets. For each OOD image, we created a counterfactual by manually removing the artefact via image processing, to assess the artefact's impact on the model's predictions. We show that OOD artefacts can boost a model's softmax confidence in its predictions, due to correlations in training data among other factors. This contradicts the common assumption that OOD artefacts should lead to more uncertain outputs, an assumption on which most confidence-based methods rely. We use this to explain why feature-based methods (e.g. Mahalanobis score) typically have greater OOD detection performance than confidence-based methods (e.g. MCP). However, we also show that feature-based methods typically perform worse at distinguishing between inputs that lead to correct and incorrect predictions (for both OOD and ID data). Following from these insights, we argue that a combination of feature-based and confidence-based methods should be used within DNN pipelines to mitigate their respective weaknesses. These project's code and OOD benchmarks are available at: https://github.com/HarryAnthony/Evaluating_OOD_detection.
## QA:
coming soon
