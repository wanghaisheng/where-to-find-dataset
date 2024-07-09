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
- content: Hang Gao et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-09 08:56:33'
tags:
- dataset
- all search terms
theme: light
title: VRSD Rethinking Similarity and Diversity for Retrieval in Large Language Models
---

# title: VRSD Rethinking Similarity and Diversity for Retrieval in Large Language Models 
## publish date: 
**2024-07-05** 
## authors: 
  Hang Gao et.al. 
## paper id
2407.04573v1
## download
[2407.04573v1](http://arxiv.org/abs/2407.04573v1)
## abstracts:
Vector retrieval algorithms are vital for semantic queries in the evolving landscape of Large Language Models (LLMs). Retrieving vectors that simultaneously meet criteria for both similarity and diversity significantly enhances the capabilities of LLM-based agents. Despite the widespread use of the Maximal Marginal Relevance (MMR) in retrieval scenarios with relevance and diversity requirements, fluctuations caused by variations in the parameter $ \lambda $ within the MMR complicate the determination of the optimization trajectory in vector spaces, thus obscuring the direction of enhancement. Moreover, there is a lack of a robust theoretical analysis for the constraints of similarity and diversity in retrieval processes. This paper introduces a novel approach to characterizing both constraints through the relationship between the sum vector and the query vector. The proximity of these vectors addresses the similarity constraint, while necessitating that individual vectors within the sum vector divergently align with the query vector to satisfy the diversity constraint. We also formulate a new combinatorial optimization challenge, taking a selection of $k$ vectors from a set of candidates such that their sum vector maximally aligns with the query vector, a problem we demonstrate to be NP-complete. This establishes the profound difficulty of pursuing similarity and diversity simultaneously in vector retrieval and lays a theoretical groundwork for further research. Additionally, we present the heuristic algorithm Vectors Retrieval with Similarity and Diversity (VRSD) which not only has a definitive optimization goal and eschews the need for preset parameters but also offers a modest reduction in time complexity compared to MMR. Empirical validation further confirm that VRSD significantly surpasses MMR across various datasets.
## QA:
coming soon
