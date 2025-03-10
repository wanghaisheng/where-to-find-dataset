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
- content: Luca Mossina et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-03-10 11:31:49'
tags:
- dataset
- all search terms
theme: light
title: Conformal Prediction for Image Segmentation Using Morphological Prediction
  Sets
---

# title: Conformal Prediction for Image Segmentation Using Morphological Prediction Sets 
## publish date: 
**2025-03-07** 
## authors: 
  Luca Mossina et.al. 
## paper id
2503.05618v1
## download
[2503.05618v1](http://arxiv.org/abs/2503.05618v1)
## abstracts:
Image segmentation is a challenging task influenced by multiple sources of uncertainty, such as the data labeling process or the sampling of training data. In this paper we focus on binary segmentation and address these challenges using conformal prediction, a family of model- and data-agnostic methods for uncertainty quantification that provide finite-sample theoretical guarantees and applicable to any pretrained predictor. Our approach involves computing nonconformity scores, a type of prediction residual, on held-out calibration data not used during training. We use dilation, one of the fundamental operations in mathematical morphology, to construct a margin added to the borders of predicted segmentation masks. At inference, the predicted set formed by the mask and its margin contains the ground-truth mask with high probability, at a confidence level specified by the user. The size of the margin serves as an indicator of predictive uncertainty for a given model and dataset. We work in a regime of minimal information as we do not require any feedback from the predictor: only the predicted masks are needed for computing the prediction sets. Hence, our method is applicable to any segmentation model, including those based on deep learning; we evaluate our approach on several medical imaging applications.
## QA:
coming soon
