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
- content: Lingrui Mei et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-07 11:36:39'
tags:
- dataset
- all search terms
theme: light
title: HiddenGuard FineGrained Safe Generation with Specialized Representation Router
---

# title: HiddenGuard FineGrained Safe Generation with Specialized Representation Router 
## publish date: 
**2024-10-03** 
## authors: 
  Lingrui Mei et.al. 
## paper id
2410.02684v1
## download
[2410.02684v1](http://arxiv.org/abs/2410.02684v1)
## abstracts:
As Large Language Models (LLMs) grow increasingly powerful, ensuring their safety and alignment with human values remains a critical challenge. Ideally, LLMs should provide informative responses while avoiding the disclosure of harmful or sensitive information. However, current alignment approaches, which rely heavily on refusal strategies, such as training models to completely reject harmful prompts or applying coarse filters are limited by their binary nature. These methods either fully deny access to information or grant it without sufficient nuance, leading to overly cautious responses or failures to detect subtle harmful content. For example, LLMs may refuse to provide basic, public information about medication due to misuse concerns. Moreover, these refusal-based methods struggle to handle mixed-content scenarios and lack the ability to adapt to context-dependent sensitivities, which can result in over-censorship of benign content. To overcome these challenges, we introduce HiddenGuard, a novel framework for fine-grained, safe generation in LLMs. HiddenGuard incorporates Prism (rePresentation Router for In-Stream Moderation), which operates alongside the LLM to enable real-time, token-level detection and redaction of harmful content by leveraging intermediate hidden states. This fine-grained approach allows for more nuanced, context-aware moderation, enabling the model to generate informative responses while selectively redacting or replacing sensitive information, rather than outright refusal. We also contribute a comprehensive dataset with token-level fine-grained annotations of potentially harmful information across diverse contexts. Our experiments demonstrate that HiddenGuard achieves over 90% in F1 score for detecting and redacting harmful content while preserving the overall utility and informativeness of the model's responses.
## QA:
coming soon
