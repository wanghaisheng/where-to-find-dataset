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
- content: Wenzhi Fang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-02-03 11:34:54'
tags:
- all search terms
- dataset on github
theme: light
title: Federated Sketching LoRA OnDevice Collaborative FineTuning of Large Language
  Models
---

# title: Federated Sketching LoRA OnDevice Collaborative FineTuning of Large Language Models 
## publish date: 
**2025-01-31** 
## authors: 
  Wenzhi Fang et.al. 
## paper id
2501.19389v1
## download
[2501.19389v1](http://arxiv.org/abs/2501.19389v1)
## abstracts:
Fine-tuning large language models (LLMs) on devices is attracting increasing interest. Recent works have fused low-rank adaptation (LoRA) techniques with federated fine-tuning to mitigate challenges associated with device model sizes and data scarcity. Still, the heterogeneity of computational resources remains a critical bottleneck: while higher-rank modules generally enhance performance, varying device capabilities constrain LoRA's feasible rank range. Existing approaches attempting to resolve this issue either lack analytical justification or impose additional computational overhead, leaving a wide gap for an efficient and theoretically-grounded solution. To address these challenges, we propose federated sketching LoRA (FSLoRA), which leverages a sketching mechanism to enable devices to selectively update submatrices of global LoRA modules maintained by the server. By adjusting the sketching ratios, which determine the ranks of the submatrices on the devices, FSLoRA flexibly adapts to device-specific communication and computational constraints. We provide a rigorous convergence analysis of FSLoRA that characterizes how the sketching ratios affect the convergence rate. Through comprehensive experiments on multiple datasets and LLM models, we demonstrate FSLoRA's superior performance compared to various baselines.
## QA:
coming soon
