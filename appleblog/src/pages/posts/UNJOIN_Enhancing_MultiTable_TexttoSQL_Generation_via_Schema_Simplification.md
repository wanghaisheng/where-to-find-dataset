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
- content: Poojah Ganesan et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-26 11:44:16'
tags:
- dataset
- all search terms
theme: light
title: UNJOIN Enhancing MultiTable TexttoSQL Generation via Schema Simplification
---

# title: UNJOIN Enhancing MultiTable TexttoSQL Generation via Schema Simplification 
## publish date: 
**2025-05-23** 
## authors: 
  Poojah Ganesan et.al. 
## paper id
2505.18122v1
## download
[2505.18122v1](http://arxiv.org/abs/2505.18122v1)
## abstracts:
Recent advances in large language models (LLMs) have greatly improved Text-to-SQL performance for single-table queries. But, it remains challenging in multi-table databases due to complex schema and relational operations. Existing methods often struggle with retrieving the right tables and columns, generating accurate JOINs and UNIONs, and generalizing across diverse schemas. To address these issues, we introduce UNJOIN, a two-stage framework that decouples the retrieval of schema elements from SQL logic generation. In the first stage, we merge the column names of all tables in the database into a single-table representation by prefixing each column with its table name. This allows the model to focus purely on accurate retrieval without being distracted by the need to write complex SQL logic. In the second stage, the SQL query is generated on this simplified schema and mapped back to the original schema by reconstructing JOINs, UNIONs, and relational logic. Evaluations on SPIDER and BIRD datasets show that UNJOIN matches or exceeds the state-of-the-art baselines. UNJOIN uses only schema information, which does not require data access or fine-tuning, making it scalable and adaptable across databases.
## QA:
coming soon
