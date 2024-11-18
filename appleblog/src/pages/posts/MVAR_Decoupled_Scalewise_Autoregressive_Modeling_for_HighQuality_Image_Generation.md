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
- content: Sucheng Ren et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-18 11:39:11'
tags:
- dataset on github
- all search terms
theme: light
title: MVAR Decoupled Scalewise Autoregressive Modeling for HighQuality Image Generation
---

# title: MVAR Decoupled Scalewise Autoregressive Modeling for HighQuality Image Generation 
## publish date: 
**2024-11-15** 
## authors: 
  Sucheng Ren et.al. 
## paper id
2411.10433v1
## download
[2411.10433v1](http://arxiv.org/abs/2411.10433v1)
## abstracts:
There exists recent work in computer vision, named VAR, that proposes a new autoregressive paradigm for image generation. Diverging from the vanilla next-token prediction, VAR structurally reformulates the image generation into a coarse to fine next-scale prediction. In this paper, we show that this scale-wise autoregressive framework can be effectively decoupled into \textit{intra-scale modeling}, which captures local spatial dependencies within each scale, and \textit{inter-scale modeling}, which models cross-scale relationships progressively from coarse-to-fine scales. This decoupling structure allows to rebuild VAR in a more computationally efficient manner. Specifically, for intra-scale modeling -- crucial for generating high-fidelity images -- we retain the original bidirectional self-attention design to ensure comprehensive modeling; for inter-scale modeling, which semantically connects different scales but is computationally intensive, we apply linear-complexity mechanisms like Mamba to substantially reduce computational overhead. We term this new framework M-VAR. Extensive experiments demonstrate that our method outperforms existing models in both image quality and generation speed. For example, our 1.5B model, with fewer parameters and faster inference speed, outperforms the largest VAR-d30-2B. Moreover, our largest model M-VAR-d32 impressively registers 1.78 FID on ImageNet 256$\times$256 and outperforms the prior-art autoregressive models LlamaGen/VAR by 0.4/0.19 and popular diffusion models LDM/DiT by 1.82/0.49, respectively. Code is avaiable at \url{https://github.com/OliverRensu/MVAR}.
## QA:
coming soon
