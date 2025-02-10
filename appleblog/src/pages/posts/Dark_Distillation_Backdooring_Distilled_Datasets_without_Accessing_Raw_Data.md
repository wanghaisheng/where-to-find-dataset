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
- content: Ziyuan Yang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-10 11:35:45'
tags:
- all search terms
- dataset
theme: light
title: Dark Distillation Backdooring Distilled Datasets without Accessing Raw Data
---

# title: Dark Distillation Backdooring Distilled Datasets without Accessing Raw Data 
## publish date: 
**2025-02-06** 
## authors: 
  Ziyuan Yang et.al. 
## paper id
2502.04229v1
## download
[2502.04229v1](http://arxiv.org/abs/2502.04229v1)
## abstracts:
Dataset distillation (DD) enhances training efficiency and reduces bandwidth by condensing large datasets into smaller synthetic ones. It enables models to achieve performance comparable to those trained on the raw full dataset and has become a widely adopted method for data sharing. However, security concerns in DD remain underexplored. Existing studies typically assume that malicious behavior originates from dataset owners during the initial distillation process, where backdoors are injected into raw datasets. In contrast, this work is the first to address a more realistic and concerning threat: attackers may intercept the dataset distribution process, inject backdoors into the distilled datasets, and redistribute them to users. While distilled datasets were previously considered resistant to backdoor attacks, we demonstrate that they remain vulnerable to such attacks. Furthermore, we show that attackers do not even require access to any raw data to inject the backdoors successfully. Specifically, our approach reconstructs conceptual archetypes for each class from the model trained on the distilled dataset. Backdoors are then injected into these archetypes to update the distilled dataset. Moreover, we ensure the updated dataset not only retains the backdoor but also preserves the original optimization trajectory, thus maintaining the knowledge of the raw dataset. To achieve this, a hybrid loss is designed to integrate backdoor information along the benign optimization trajectory, ensuring that previously learned information is not forgotten. Extensive experiments demonstrate that distilled datasets are highly vulnerable to backdoor attacks, with risks pervasive across various raw datasets, distillation methods, and downstream training strategies. Moreover, our attack method is efficient, capable of synthesizing a malicious distilled dataset in under one minute in certain cases.
## QA:
coming soon
