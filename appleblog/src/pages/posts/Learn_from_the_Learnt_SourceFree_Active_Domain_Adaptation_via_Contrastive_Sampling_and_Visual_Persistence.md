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
- content: Mengyao Lyu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-29 11:32:42'
tags:
- dataset on github
- all search terms
theme: light
title: Learn from the Learnt SourceFree Active Domain Adaptation via Contrastive Sampling
  and Visual Persistence
---

# title: Learn from the Learnt SourceFree Active Domain Adaptation via Contrastive Sampling and Visual Persistence 
## publish date: 
**2024-07-26** 
## authors: 
  Mengyao Lyu et.al. 
## paper id
2407.18899v1
## download
[2407.18899v1](http://arxiv.org/abs/2407.18899v1)
## abstracts:
Domain Adaptation (DA) facilitates knowledge transfer from a source domain to a related target domain. This paper investigates a practical DA paradigm, namely Source data-Free Active Domain Adaptation (SFADA), where source data becomes inaccessible during adaptation, and a minimum amount of annotation budget is available in the target domain. Without referencing the source data, new challenges emerge in identifying the most informative target samples for labeling, establishing cross-domain alignment during adaptation, and ensuring continuous performance improvements through the iterative query-and-adaptation process. In response, we present learn from the learnt (LFTL), a novel paradigm for SFADA to leverage the learnt knowledge from the source pretrained model and actively iterated models without extra overhead. We propose Contrastive Active Sampling to learn from the hypotheses of the preceding model, thereby querying target samples that are both informative to the current model and persistently challenging throughout active learning. During adaptation, we learn from features of actively selected anchors obtained from previous intermediate models, so that the Visual Persistence-guided Adaptation can facilitate feature distribution alignment and active sample exploitation. Extensive experiments on three widely-used benchmarks show that our LFTL achieves state-of-the-art performance, superior computational efficiency and continuous improvements as the annotation budget increases. Our code is available at https://github.com/lyumengyao/lftl.
## QA:
coming soon
