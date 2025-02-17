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
- content: Xiaoliu Guan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-17 11:35:44'
tags:
- dataset
- all search terms
theme: light
title: Redistribute Ensemble Training for Mitigating Memorization in Diffusion Models
---

# title: Redistribute Ensemble Training for Mitigating Memorization in Diffusion Models 
## publish date: 
**2025-02-13** 
## authors: 
  Xiaoliu Guan et.al. 
## paper id
2502.09434v1
## download
[2502.09434v1](http://arxiv.org/abs/2502.09434v1)
## abstracts:
Diffusion models, known for their tremendous ability to generate high-quality samples, have recently raised concerns due to their data memorization behavior, which poses privacy risks. Recent methods for memory mitigation have primarily addressed the issue within the context of the text modality in cross-modal generation tasks, restricting their applicability to specific conditions. In this paper, we propose a novel method for diffusion models from the perspective of visual modality, which is more generic and fundamental for mitigating memorization. Directly exposing visual data to the model increases memorization risk, so we design a framework where models learn through proxy model parameters instead. Specially, the training dataset is divided into multiple shards, with each shard training a proxy model, then aggregated to form the final model. Additionally, practical analysis of training losses illustrates that the losses for easily memorable images tend to be obviously lower. Thus, we skip the samples with abnormally low loss values from the current mini-batch to avoid memorizing. However, balancing the need to skip memorization-prone samples while maintaining sufficient training data for high-quality image generation presents a key challenge. Thus, we propose IET-AGC+, which redistributes highly memorizable samples between shards, to mitigate these samples from over-skipping. Furthermore, we dynamically augment samples based on their loss values to further reduce memorization. Extensive experiments and analysis on four datasets show that our method successfully reduces memory capacity while maintaining performance. Moreover, we fine-tune the pre-trained diffusion models, e.g., Stable Diffusion, and decrease the memorization score by 46.7\%, demonstrating the effectiveness of our method. Code is available in: https://github.com/liuxiao-guan/IET_AGC.
## QA:
coming soon
