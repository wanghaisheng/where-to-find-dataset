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
- content: Morgan E. Prior et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-23 11:35:13'
tags:
- dataset
- all search terms
theme: light
title: Generalized compression and compressive search of large datasets
---

# title: Generalized compression and compressive search of large datasets 
## publish date: 
**2024-09-18** 
## authors: 
  Morgan E. Prior et.al. 
## paper id
2409.12161v1
## download
[2409.12161v1](http://arxiv.org/abs/2409.12161v1)
## abstracts:
The Big Data explosion has necessitated the development of search algorithms that scale sub-linearly in time and memory.   While compression algorithms and search algorithms do exist independently, few algorithms offer both, and those which do are domain-specific.   We present panCAKES, a novel approach to compressive search, i.e., a way to perform $k$-NN and $\rho$-NN search on compressed data while only decompressing a small, relevant, portion of the data.   panCAKES assumes the manifold hypothesis and leverages the low-dimensional structure of the data to compress and search it efficiently.   panCAKES is generic over any distance function for which the distance between two points is proportional to the memory cost of storing an encoding of one in terms of the other.   This property holds for many widely-used distance functions, e.g. string edit distances (Levenshtein, Needleman-Wunsch, etc.) and set dissimilarity measures (Jaccard, Dice, etc.).   We benchmark panCAKES on a variety of datasets, including genomic, proteomic, and set data.   We compare compression ratios to gzip, and search performance between the compressed and uncompressed versions of the same dataset.   panCAKES achieves compression ratios close to those of gzip, while offering sub-linear time performance for $k$-NN and $\rho$-NN search.   We conclude that panCAKES is an efficient, general-purpose algorithm for exact compressive search on large datasets that obey the manifold hypothesis.   We provide an open-source implementation of panCAKES in the Rust programming language.
## QA:
coming soon
