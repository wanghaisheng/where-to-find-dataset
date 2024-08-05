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
- content: Ying Zhang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-05 11:32:47'
tags:
- all search terms
- dataset
theme: light
title: Reconsidering Token Embeddings with the Definitions for Pretrained Language
  Models
---

# title: Reconsidering Token Embeddings with the Definitions for Pretrained Language Models 
## publish date: 
**2024-08-02** 
## authors: 
  Ying Zhang et.al. 
## paper id
2408.01308v1
## download
[2408.01308v1](http://arxiv.org/abs/2408.01308v1)
## abstracts:
Learning token embeddings based on token co-occurrence statistics has proven effective for both pre-training and fine-tuning in natural language processing. However, recent studies have pointed out the distribution of learned embeddings degenerates into anisotropy, and even pre-trained language models (PLMs) suffer from a loss of semantics-related information in embeddings for low-frequency tokens. This study first analyzes fine-tuning dynamics of a PLM, BART-large, and demonstrates its robustness against degeneration. On the basis of this finding, we propose DefinitionEMB, a method that utilizes definitions to construct isotropically distributed and semantics-related token embeddings for PLMs while maintaining original robustness during fine-tuning. Our experiments demonstrate the effectiveness of leveraging definitions from Wiktionary to construct such embeddings for RoBERTa-base and BART-large. Furthermore, the constructed embeddings for low-frequency tokens improve the performance of these models across various GLUE and four text summarization datasets.
## QA:
coming soon
