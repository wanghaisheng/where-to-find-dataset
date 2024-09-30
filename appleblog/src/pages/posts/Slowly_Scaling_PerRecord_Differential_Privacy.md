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
- content: Brian Finley et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-30 11:37:55'
tags:
- all search terms
- dataset
theme: light
title: Slowly Scaling PerRecord Differential Privacy
---

# title: Slowly Scaling PerRecord Differential Privacy 
## publish date: 
**2024-09-26** 
## authors: 
  Brian Finley et.al. 
## paper id
2409.18118v1
## download
[2409.18118v1](http://arxiv.org/abs/2409.18118v1)
## abstracts:
We develop formal privacy mechanisms for releasing statistics from data with many outlying values, such as income data. These mechanisms ensure that a per-record differential privacy guarantee degrades slowly in the protected records' influence on the statistics being released.   Formal privacy mechanisms generally add randomness, or "noise," to published statistics. If a noisy statistic's distribution changes little with the addition or deletion of a single record in the underlying dataset, an attacker looking at this statistic will find it plausible that any particular record was present or absent, preserving the records' privacy. More influential records -- those whose addition or deletion would change the statistics' distribution more -- typically suffer greater privacy loss. The per-record differential privacy framework quantifies these record-specific privacy guarantees, but existing mechanisms let these guarantees degrade rapidly (linearly or quadratically) with influence. While this may be acceptable in cases with some moderately influential records, it results in unacceptably high privacy losses when records' influence varies widely, as is common in economic data.   We develop mechanisms with privacy guarantees that instead degrade as slowly as logarithmically with influence. These mechanisms allow for the accurate, unbiased release of statistics, while providing meaningful protection for highly influential records. As an example, we consider the private release of sums of unbounded establishment data such as payroll, where our mechanisms extend meaningful privacy protection even to very large establishments. We evaluate these mechanisms empirically and demonstrate their utility.
## QA:
coming soon
