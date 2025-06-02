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
- content: Bojia Zi et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-06-02 11:45:57'
tags:
- dataset on github
- all search terms
theme: light
title: MiniMaxRemover Taming Bad Noise Helps Video Object Removal
---

# title: MiniMaxRemover Taming Bad Noise Helps Video Object Removal 
## publish date: 
**2025-05-30** 
## authors: 
  Bojia Zi et.al. 
## paper id
2505.24873v1
## download
[2505.24873v1](http://arxiv.org/abs/2505.24873v1)
## abstracts:
Recent advances in video diffusion models have driven rapid progress in video editing techniques. However, video object removal, a critical subtask of video editing, remains challenging due to issues such as hallucinated objects and visual artifacts. Furthermore, existing methods often rely on computationally expensive sampling procedures and classifier-free guidance (CFG), resulting in slow inference. To address these limitations, we propose MiniMax-Remover, a novel two-stage video object removal approach. Motivated by the observation that text condition is not best suited for this task, we simplify the pretrained video generation model by removing textual input and cross-attention layers, resulting in a more lightweight and efficient model architecture in the first stage. In the second stage, we distilled our remover on successful videos produced by the stage-1 model and curated by human annotators, using a minimax optimization strategy to further improve editing quality and inference speed. Specifically, the inner maximization identifies adversarial input noise ("bad noise") that makes failure removals, while the outer minimization step trains the model to generate high-quality removal results even under such challenging conditions. As a result, our method achieves a state-of-the-art video object removal results with as few as 6 sampling steps and doesn't rely on CFG, significantly improving inference efficiency. Extensive experiments demonstrate the effectiveness and superiority of MiniMax-Remover compared to existing methods. Codes and Videos are available at: https://minimax-remover.github.io.
## QA:
coming soon
