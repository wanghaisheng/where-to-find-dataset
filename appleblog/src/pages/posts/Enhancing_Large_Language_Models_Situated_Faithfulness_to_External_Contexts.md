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
- content: Yukun Huang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-21 11:37:21'
tags:
- all search terms
- dataset
theme: light
title: Enhancing Large Language Models Situated Faithfulness to External Contexts
---

# title: Enhancing Large Language Models Situated Faithfulness to External Contexts 
## publish date: 
**2024-10-18** 
## authors: 
  Yukun Huang et.al. 
## paper id
2410.14675v1
## download
[2410.14675v1](http://arxiv.org/abs/2410.14675v1)
## abstracts:
Large Language Models (LLMs) are often augmented with external information as contexts, but this external information can sometimes be inaccurate or even intentionally misleading. We argue that robust LLMs should demonstrate situated faithfulness, dynamically calibrating their trust in external information based on their confidence in the internal knowledge and the external context. To benchmark this capability, we evaluate LLMs across several QA datasets, including a newly created dataset called RedditQA featuring in-the-wild incorrect contexts sourced from Reddit posts. We show that when provided with both correct and incorrect contexts, both open-source and proprietary models tend to overly rely on external information, regardless of its factual accuracy. To enhance situated faithfulness, we propose two approaches: Self-Guided Confidence Reasoning (SCR) and Rule-Based Confidence Reasoning (RCR). SCR enables models to self-access the confidence of external information relative to their own internal knowledge to produce the most accurate answer. RCR, in contrast, extracts explicit confidence signals from the LLM and determines the final answer using predefined rules. Our results show that for LLMs with strong reasoning capabilities, such as GPT-4o and GPT-4o mini, SCR outperforms RCR, achieving improvements of up to 24.2% over a direct input augmentation baseline. Conversely, for a smaller model like Llama-3-8B, RCR outperforms SCR. Fine-tuning SCR with our proposed Confidence Reasoning Direct Preference Optimization (CR-DPO) method improves performance on both seen and unseen datasets, yielding an average improvement of 8.9% on Llama-3-8B. In addition to quantitative results, we offer insights into the relative strengths of SCR and RCR. Our findings highlight promising avenues for improving situated faithfulness in LLMs. The data and code are released.
## QA:
coming soon
