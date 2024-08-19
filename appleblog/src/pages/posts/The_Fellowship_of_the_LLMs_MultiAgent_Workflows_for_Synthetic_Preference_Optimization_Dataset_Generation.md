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
- content: Samee Arif et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-19 11:32:25'
tags:
- all search terms
- dataset
theme: light
title: The Fellowship of the LLMs MultiAgent Workflows for Synthetic Preference Optimization
  Dataset Generation
---

# title: The Fellowship of the LLMs MultiAgent Workflows for Synthetic Preference Optimization Dataset Generation 
## publish date: 
**2024-08-16** 
## authors: 
  Samee Arif et.al. 
## paper id
2408.08688v1
## download
[2408.08688v1](http://arxiv.org/abs/2408.08688v1)
## abstracts:
This paper presents and evaluates multi-agent workflows for synthetic Preference Optimization (PO) dataset generation. PO dataset generation requires two modules: (1) response evaluation, and (2) response generation. In the response evaluation module, the responses from Large Language Models (LLMs) are evaluated and ranked - a task typically carried out by human annotators that we automate using LLMs. We assess the response evaluation module in a 2 step process. In step 1, we assess LLMs as evaluators using three distinct prompting strategies. In step 2, we apply the winning prompting strategy to compare the performance of LLM-as-a-Judge, LLMs-as-a-Jury, and LLM Debate. In each step, we use inter-rater agreement using Cohen's Kappa between human annotators and LLMs. For the response generation module, we compare different configurations for the LLM Feedback Loop using the identified LLM evaluator configuration. We use the win rate (the fraction of times a generation framework is selected as the best by an LLM evaluator) to determine the best multi-agent configuration for generation. After identifying the best configurations for both modules, we use models from the GPT, Gemma, and Llama families to generate our PO datasets using the above pipeline. We generate two types of PO datasets, one to improve the generation capabilities of individual LLM and the other to improve the multi-agent workflow. Our evaluation shows that GPT-4o-as-a-Judge is more consistent across datasets when the candidate responses do not include responses from the GPT family. Additionally, we find that the LLM Feedback Loop, with Llama as the generator and Gemma as the reviewer, achieves a notable 71.8% and 73.8% win rate over single-agent Llama and Gemma, respectively.
## QA:
coming soon
