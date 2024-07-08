---
layout: '../../layouts/MarkdownPost.astro'
title: '**Using LLMs to label medical papers according to the CIViC evidence model**'
pubDate: '2024-07-09 06:48:34'
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: '['all search terms', 'Image Classification']' 
theme: 'light'
featured: true

meta:
 - name: author
   content: Markus Hisch et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.04466v1
## download
[2407.04466v1](http://arxiv.org/abs/2407.04466v1)
## abstracts:
We introduce the sequence classification problem CIViC Evidence to the field of medical NLP. CIViC Evidence denotes the multi-label classification problem of assigning labels of clinical evidence to abstracts of scientific papers which have examined various combinations of genomic variants, cancer types, and treatment approaches. We approach CIViC Evidence using different language models: We fine-tune pretrained checkpoints of BERT and RoBERTa on the CIViC Evidence dataset and challenge their performance with models of the same architecture which have been pretrained on domain-specific text. In this context, we find that BiomedBERT and BioLinkBERT can outperform BERT on CIViC Evidence (+0.8% and +0.9% absolute improvement in class-support weighted F1 score). All transformer-based models show a clear performance edge when compared to a logistic regression trained on bigram tf-idf scores (+1.5 - 2.7% improved F1 score). We compare the aforementioned BERT-like models to OpenAI's GPT-4 in a few-shot setting (on a small subset of our original test dataset), demonstrating that, without additional prompt-engineering or fine-tuning, GPT-4 performs worse on CIViC Evidence than our six fine-tuned models (66.1% weighted F1 score compared to 71.8% for the best fine-tuned model). However, performance gets reasonably close to the benchmark of a logistic regression model trained on bigram tf-idf scores (67.7% weighted F1 score).
## QA:
coming soon
