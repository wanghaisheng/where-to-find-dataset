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
- content: Daeun Lee et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-25 11:39:20'
tags:
- all search terms
- dataset on github
theme: light
title: VideoRepair Improving TexttoVideo Generation via Misalignment Evaluation and
  Localized Refinement
---

# title: VideoRepair Improving TexttoVideo Generation via Misalignment Evaluation and Localized Refinement 
## publish date: 
**2024-11-22** 
## authors: 
  Daeun Lee et.al. 
## paper id
2411.15115v1
## download
[2411.15115v1](http://arxiv.org/abs/2411.15115v1)
## abstracts:
Recent text-to-video (T2V) diffusion models have demonstrated impressive generation capabilities across various domains. However, these models often generate videos that have misalignments with text prompts, especially when the prompts describe complex scenes with multiple objects and attributes. To address this, we introduce VideoRepair, a novel model-agnostic, training-free video refinement framework that automatically identifies fine-grained text-video misalignments and generates explicit spatial and textual feedback, enabling a T2V diffusion model to perform targeted, localized refinements. VideoRepair consists of four stages: In (1) video evaluation, we detect misalignments by generating fine-grained evaluation questions and answering those questions with MLLM. In (2) refinement planning, we identify accurately generated objects and then create localized prompts to refine other areas in the video. Next, in (3) region decomposition, we segment the correctly generated area using a combined grounding module. We regenerate the video by adjusting the misaligned regions while preserving the correct regions in (4) localized refinement. On two popular video generation benchmarks (EvalCrafter and T2V-CompBench), VideoRepair substantially outperforms recent baselines across various text-video alignment metrics. We provide a comprehensive analysis of VideoRepair components and qualitative examples.
## QA:
coming soon
