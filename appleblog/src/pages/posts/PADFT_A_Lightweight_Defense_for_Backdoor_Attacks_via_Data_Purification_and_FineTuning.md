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
- content: Yukai Xu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-23 11:35:17'
tags:
- dataset
- all search terms
theme: light
title: PADFT A Lightweight Defense for Backdoor Attacks via Data Purification and
  FineTuning
---

# title: PADFT A Lightweight Defense for Backdoor Attacks via Data Purification and FineTuning 
## publish date: 
**2024-09-18** 
## authors: 
  Yukai Xu et.al. 
## paper id
2409.12072v1
## download
[2409.12072v1](http://arxiv.org/abs/2409.12072v1)
## abstracts:
Backdoor attacks pose a significant threat to deep neural networks, particularly as recent advancements have led to increasingly subtle implantation, making the defense more challenging. Existing defense mechanisms typically rely on an additional clean dataset as a standard reference and involve retraining an auxiliary model or fine-tuning the entire victim model. However, these approaches are often computationally expensive and not always feasible in practical applications. In this paper, we propose a novel and lightweight defense mechanism, termed PAD-FT, that does not require an additional clean dataset and fine-tunes only a very small part of the model to disinfect the victim model. To achieve this, our approach first introduces a simple data purification process to identify and select the most-likely clean data from the poisoned training dataset. The self-purified clean dataset is then used for activation clipping and fine-tuning only the last classification layer of the victim model. By integrating data purification, activation clipping, and classifier fine-tuning, our mechanism PAD-FT demonstrates superior effectiveness across multiple backdoor attack methods and datasets, as confirmed through extensive experimental evaluation.
## QA:
coming soon
