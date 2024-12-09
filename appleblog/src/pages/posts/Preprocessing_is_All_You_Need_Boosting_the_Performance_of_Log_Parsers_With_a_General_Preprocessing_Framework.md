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
- content: Qiaolin Qin et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-09 11:41:08'
tags:
- all search terms
- dataset on github
theme: light
title: Preprocessing is All You Need Boosting the Performance of Log Parsers With
  a General Preprocessing Framework
---

# title: Preprocessing is All You Need Boosting the Performance of Log Parsers With a General Preprocessing Framework 
## publish date: 
**2024-12-06** 
## authors: 
  Qiaolin Qin et.al. 
## paper id
2412.05254v1
## download
[2412.05254v1](http://arxiv.org/abs/2412.05254v1)
## abstracts:
Log parsing has been a long-studied area in software engineering due to its importance in identifying dynamic variables and constructing log templates. Prior work has proposed many statistic-based log parsers (e.g., Drain), which are highly efficient; they, unfortunately, met the bottleneck of parsing performance in comparison to semantic-based log parsers, which require labeling and more computational resources. Meanwhile, we noticed that previous studies mainly focused on parsing and often treated preprocessing as an ad hoc step (e.g., masking numbers). However, we argue that both preprocessing and parsing are essential for log parsers to identify dynamic variables: the lack of understanding of preprocessing may hinder the optimal use of parsers and future research. Therefore, our work studied existing log preprocessing approaches based on Loghub, a popular log parsing benchmark. We developed a general preprocessing framework with our findings and evaluated its impact on existing parsers. Our experiments show that the preprocessing framework significantly boosts the performance of four state-of-the-art statistic-based parsers. Drain, the best statistic-based parser, obtained improvements across all four parsing metrics (e.g., F1 score of template accuracy, FTA, increased by 108.9%). Compared to semantic-based parsers, it achieved a 28.3% improvement in grouping accuracy (GA), 38.1% in FGA, and an 18.6% increase in FTA. Our work pioneers log preprocessing and provides a generalizable framework to enhance log parsing.
## QA:
coming soon
