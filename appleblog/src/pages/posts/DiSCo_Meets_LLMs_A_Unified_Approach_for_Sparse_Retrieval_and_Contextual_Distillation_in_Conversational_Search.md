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
- content: Simon Lupart et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-21 11:37:24'
tags:
- all search terms
- dataset
theme: light
title: DiSCo Meets LLMs A Unified Approach for Sparse Retrieval and Contextual Distillation
  in Conversational Search
---

# title: DiSCo Meets LLMs A Unified Approach for Sparse Retrieval and Contextual Distillation in Conversational Search 
## publish date: 
**2024-10-18** 
## authors: 
  Simon Lupart et.al. 
## paper id
2410.14609v1
## download
[2410.14609v1](http://arxiv.org/abs/2410.14609v1)
## abstracts:
Conversational Search (CS) is the task of retrieving relevant documents from a corpus within a conversational context, combining retrieval with conversational context modeling. With the explosion of Large Language Models (LLMs), the CS field has seen major improvements with LLMs rewriting user queries, accounting for conversational context. However, engaging LLMs at inference time harms efficiency. Current methods address this by distilling embeddings from human-rewritten queries to learn the context modeling task. Yet, these approaches predominantly focus on context modeling, and only treat the contrastive component of the retrieval task within a distillation-independent loss term. To address these limitations, we propose a new distillation method, as a relaxation of the previous objective, unifying retrieval and context modeling. We relax the existing training objectives by distilling similarity scores between conversations and documents, rather than relying solely on representation learning. Our proposed distillation objective allows for more freedom in the representation space and leverages the contrastive nature of document relevance. Through experiments on Learned Sparse Retrieval (LSR) across 5 CS datasets, our approach demonstrates substantial improvements in both in-domain and out-of-domain retrieval performance, outperforming state-of-the-art with gains of up to 6 points in recall for out-of-domain datasets. Additionally, through the relaxation of the objective, we propose a multi-teacher distillation, using multiple LLMs as teachers, yielding additional gains, and outperforming the teachers themselves in in-domain experiments. Finally, analysis of the sparsity of the models reveals that our distillation allows for better control over the sparsity of the trained models.
## QA:
coming soon
