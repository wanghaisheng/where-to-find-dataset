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
- content: Rob A. J. de Mooij et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-30 11:37:56'
tags:
- all search terms
- dataset
theme: light
title: Selfsupervised Pretraining for Cardiovascular Magnetic Resonance Cine Segmentation
---

# title: Selfsupervised Pretraining for Cardiovascular Magnetic Resonance Cine Segmentation 
## publish date: 
**2024-09-26** 
## authors: 
  Rob A. J. de Mooij et.al. 
## paper id
2409.18100v1
## download
[2409.18100v1](http://arxiv.org/abs/2409.18100v1)
## abstracts:
Self-supervised pretraining (SSP) has shown promising results in learning from large unlabeled datasets and, thus, could be useful for automated cardiovascular magnetic resonance (CMR) short-axis cine segmentation. However, inconsistent reports of the benefits of SSP for segmentation have made it difficult to apply SSP to CMR. Therefore, this study aimed to evaluate SSP methods for CMR cine segmentation.   To this end, short-axis cine stacks of 296 subjects (90618 2D slices) were used for unlabeled pretraining with four SSP methods; SimCLR, positional contrastive learning, DINO, and masked image modeling (MIM). Subsets of varying numbers of subjects were used for supervised fine-tuning of 2D models for each SSP method, as well as to train a 2D baseline model from scratch. The fine-tuned models were compared to the baseline using the 3D Dice similarity coefficient (DSC) in a test dataset of 140 subjects.   The SSP methods showed no performance gains with the largest supervised fine-tuning subset compared to the baseline (DSC = 0.89). When only 10 subjects (231 2D slices) are available for supervised training, SSP using MIM (DSC = 0.86) improves over training from scratch (DSC = 0.82).   This study found that SSP is valuable for CMR cine segmentation when labeled training data is scarce, but does not aid state-of-the-art deep learning methods when ample labeled data is available. Moreover, the choice of SSP method is important. The code is publicly available at: https://github.com/q-cardIA/ssp-cmr-cine-segmentation
## QA:
coming soon
