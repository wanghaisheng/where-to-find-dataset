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
- content: Derong Xu Xinhang Li et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-30 11:35:41'
tags:
- all search terms
- dataset
theme: light
title: Harnessing Large Language Models for Knowledge Graph Question Answering via
  Adaptive MultiAspect RetrievalAugmentation
---

# title: Harnessing Large Language Models for Knowledge Graph Question Answering via Adaptive MultiAspect RetrievalAugmentation 
## publish date: 
**2024-12-24** 
## authors: 
  Derong Xu Xinhang Li et.al. 
## paper id
2412.18537v1
## download
[2412.18537v1](http://arxiv.org/abs/2412.18537v1)
## abstracts:
Large Language Models (LLMs) demonstrate remarkable capabilities, yet struggle with hallucination and outdated knowledge when tasked with complex knowledge reasoning, resulting in factually incorrect outputs. Previous studies have attempted to mitigate it by retrieving factual knowledge from large-scale knowledge graphs (KGs) to assist LLMs in logical reasoning and prediction of answers. However, this kind of approach often introduces noise and irrelevant data, especially in situations with extensive context from multiple knowledge aspects. In this way, LLM attention can be potentially mislead from question and relevant information. In our study, we introduce an Adaptive Multi-Aspect Retrieval-augmented over KGs (Amar) framework. This method retrieves knowledge including entities, relations, and subgraphs, and converts each piece of retrieved text into prompt embeddings. The Amar framework comprises two key sub-components: 1) a self-alignment module that aligns commonalities among entities, relations, and subgraphs to enhance retrieved text, thereby reducing noise interference; 2) a relevance gating module that employs a soft gate to learn the relevance score between question and multi-aspect retrieved data, to determine which information should be used to enhance LLMs' output, or even filtered altogether. Our method has achieved state-of-the-art performance on two common datasets, WebQSP and CWQ, showing a 1.9\% improvement in accuracy over its best competitor and a 6.6\% improvement in logical form generation over a method that directly uses retrieved text as context prompts. These results demonstrate the effectiveness of Amar in improving the reasoning of LLMs.
## QA:
coming soon
