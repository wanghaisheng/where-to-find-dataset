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
- content: Sahil Sethi et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-04-14 11:41:11'
tags:
- dataset
- all search terms
theme: light
title: ProtoECGNet CaseBased Interpretable Deep Learning for MultiLabel ECG Classification
  with Contrastive Learning
---

# title: ProtoECGNet CaseBased Interpretable Deep Learning for MultiLabel ECG Classification with Contrastive Learning 
## publish date: 
**2025-04-11** 
## authors: 
  Sahil Sethi et.al. 
## paper id
2504.08713v1
## download
[2504.08713v1](http://arxiv.org/abs/2504.08713v1)
## abstracts:
Deep learning-based electrocardiogram (ECG) classification has shown impressive performance but clinical adoption has been slowed by the lack of transparent and faithful explanations. Post hoc methods such as saliency maps may fail to reflect a model's true decision process. Prototype-based reasoning offers a more transparent alternative by grounding decisions in similarity to learned representations of real ECG segments, enabling faithful, case-based explanations. We introduce ProtoECGNet, a prototype-based deep learning model for interpretable, multi-label ECG classification. ProtoECGNet employs a structured, multi-branch architecture that reflects clinical interpretation workflows: it integrates a 1D CNN with global prototypes for rhythm classification, a 2D CNN with time-localized prototypes for morphology-based reasoning, and a 2D CNN with global prototypes for diffuse abnormalities. Each branch is trained with a prototype loss designed for multi-label learning, combining clustering, separation, diversity, and a novel contrastive loss that encourages appropriate separation between prototypes of unrelated classes while allowing clustering for frequently co-occurring diagnoses. We evaluate ProtoECGNet on all 71 diagnostic labels from the PTB-XL dataset, demonstrating competitive performance relative to state-of-the-art black-box models while providing structured, case-based explanations. To assess prototype quality, we conduct a structured clinician review of the final model's projected prototypes, finding that they are rated as representative and clear. ProtoECGNet shows that prototype learning can be effectively scaled to complex, multi-label time-series classification, offering a practical path toward transparent and trustworthy deep learning models for clinical decision support.
## QA:
coming soon
