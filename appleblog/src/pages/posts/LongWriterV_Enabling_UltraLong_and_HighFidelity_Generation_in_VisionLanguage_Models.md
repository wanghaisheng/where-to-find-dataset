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
- content: Shangqing Tu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-24 11:36:35'
tags:
- dataset
- all search terms
theme: light
title: LongWriterV Enabling UltraLong and HighFidelity Generation in VisionLanguage
  Models
---

# title: LongWriterV Enabling UltraLong and HighFidelity Generation in VisionLanguage Models 
## publish date: 
**2025-02-20** 
## authors: 
  Shangqing Tu et.al. 
## paper id
2502.14834v1
## download
[2502.14834v1](http://arxiv.org/abs/2502.14834v1)
## abstracts:
Existing Large Vision-Language Models (LVLMs) can process inputs with context lengths up to 128k visual and text tokens, yet they struggle to generate coherent outputs beyond 1,000 words. We find that the primary limitation is the absence of long output examples during supervised fine-tuning (SFT). To tackle this issue, we introduce LongWriter-V-22k, a SFT dataset comprising 22,158 examples, each with multiple input images, an instruction, and corresponding outputs ranging from 0 to 10,000 words. Moreover, to achieve long outputs that maintain high-fidelity to the input images, we employ Direct Preference Optimization (DPO) to the SFT model. Given the high cost of collecting human feedback for lengthy outputs (e.g., 3,000 words), we propose IterDPO, which breaks long outputs into segments and uses iterative corrections to form preference pairs with the original outputs. Additionally, we develop MMLongBench-Write, a benchmark featuring six tasks to evaluate the long-generation capabilities of VLMs. Our 7B parameter model, trained with LongWriter-V-22k and IterDPO, achieves impressive performance on this benchmark, outperforming larger proprietary models like GPT-4o. Code and data: https://github.com/THU-KEG/LongWriter-V
## QA:
coming soon
