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
- content: Mothilal Asokan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-02 01:35:16'
tags:
- all search terms
- dataset
theme: light
title: A Federated LearningFriendly Approach for ParameterEfficient FineTuning of
  SAM in 3D Segmentation
---

# title: A Federated LearningFriendly Approach for ParameterEfficient FineTuning of SAM in 3D Segmentation 
## publish date: 
**2024-07-31** 
## authors: 
  Mothilal Asokan et.al. 
## paper id
2407.21739v1
## download
[2407.21739v1](http://arxiv.org/abs/2407.21739v1)
## abstracts:
Adapting foundation models for medical image analysis requires finetuning them on a considerable amount of data because of extreme distribution shifts between natural (source) data used for pretraining and medical (target) data. However, collecting task-specific medical data for such finetuning at a central location raises many privacy concerns. Although Federated learning (FL) provides an effective means for training on private decentralized data, communication costs in federating large foundation models can quickly become a significant bottleneck, impacting the solution's scalability. In this work, we address this problem of efficient communication while ensuring effective learning in FL by combining the strengths of Parameter-Efficient Fine-tuning (PEFT) with FL. Specifically, we study plug-and-play Low-Rank Adapters (LoRA) in a federated manner to adapt the Segment Anything Model (SAM) for 3D medical image segmentation. Unlike prior works that utilize LoRA and finetune the entire decoder, we critically analyze the contribution of each granular component of SAM on finetuning performance. Thus, we identify specific layers to be federated that are very efficient in terms of communication cost while producing on-par accuracy. Our experiments show that retaining the parameters of the SAM model (including most of the decoder) in their original state during adaptation is beneficial because fine-tuning on small datasets tends to distort the inherent capabilities of the underlying foundation model. On Fed-KiTS, our approach decreases communication cost (~48x) compared to full fine-tuning while increasing performance (~6% Dice score) in 3D segmentation tasks. Our approach performs similar to SAMed while achieving ~2.8x reduction in communication and parameters to be finetuned. We further validate our approach with experiments on Fed-IXI and Prostate MRI datasets.
## QA:
coming soon
