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
- content: Tianyu Chen et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-04 11:37:43'
tags:
- all search terms
- dataset
theme: light
title: Identifying General Mechanism Shifts in Linear Causal Representations
---

# title: Identifying General Mechanism Shifts in Linear Causal Representations 
## publish date: 
**2024-10-31** 
## authors: 
  Tianyu Chen et.al. 
## paper id
2410.24059v1
## download
[2410.24059v1](http://arxiv.org/abs/2410.24059v1)
## abstracts:
We consider the linear causal representation learning setting where we observe a linear mixing of $d$ unknown latent factors, which follow a linear structural causal model. Recent work has shown that it is possible to recover the latent factors as well as the underlying structural causal model over them, up to permutation and scaling, provided that we have at least $d$ environments, each of which corresponds to perfect interventions on a single latent node (factor). After this powerful result, a key open problem faced by the community has been to relax these conditions: allow for coarser than perfect single-node interventions, and allow for fewer than $d$ of them, since the number of latent factors $d$ could be very large. In this work, we consider precisely such a setting, where we allow a smaller than $d$ number of environments, and also allow for very coarse interventions that can very coarsely \textit{change the entire causal graph over the latent factors}. On the flip side, we relax what we wish to extract to simply the \textit{list of nodes that have shifted between one or more environments}. We provide a surprising identifiability result that it is indeed possible, under some very mild standard assumptions, to identify the set of shifted nodes. Our identifiability proof moreover is a constructive one: we explicitly provide necessary and sufficient conditions for a node to be a shifted node, and show that we can check these conditions given observed data. Our algorithm lends itself very naturally to the sample setting where instead of just interventional distributions, we are provided datasets of samples from each of these distributions. We corroborate our results on both synthetic experiments as well as an interesting psychometric dataset. The code can be found at https://github.com/TianyuCodings/iLCS.
## QA:
coming soon
