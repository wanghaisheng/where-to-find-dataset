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
- content: Roel Koopman et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-12 11:32:47'
tags:
- dataset
- all search terms
theme: light
title: Overcoming the Limitations of Layer Synchronization in Spiking Neural Networks
---

# title: Overcoming the Limitations of Layer Synchronization in Spiking Neural Networks 
## publish date: 
**2024-08-09** 
## authors: 
  Roel Koopman et.al. 
## paper id
2408.05098v1
## download
[2408.05098v1](http://arxiv.org/abs/2408.05098v1)
## abstracts:
Currently, neural-network processing in machine learning applications relies on layer synchronization, whereby neurons in a layer aggregate incoming currents from all neurons in the preceding layer, before evaluating their activation function. This is practiced even in artificial Spiking Neural Networks (SNNs), which are touted as consistent with neurobiology, in spite of processing in the brain being, in fact asynchronous. A truly asynchronous system however would allow all neurons to evaluate concurrently their threshold and emit spikes upon receiving any presynaptic current. Omitting layer synchronization is potentially beneficial, for latency and energy efficiency, but asynchronous execution of models previously trained with layer synchronization may entail a mismatch in network dynamics and performance. We present a study that documents and quantifies this problem in three datasets on our simulation environment that implements network asynchrony, and we show that models trained with layer synchronization either perform sub-optimally in absence of the synchronization, or they will fail to benefit from any energy and latency reduction, when such a mechanism is in place. We then "make ends meet" and address the problem with unlayered backprop, a novel backpropagation-based training method, for learning models suitable for asynchronous processing. We train with it models that use different neuron execution scheduling strategies, and we show that although their neurons are more reactive, these models consistently exhibit lower overall spike density (up to 50%), reach a correct decision faster (up to 2x) without integrating all spikes, and achieve superior accuracy (up to 10% higher). Our findings suggest that asynchronous event-based (neuromorphic) AI computing is indeed more efficient, but we need to seriously rethink how we train our SNN models, to benefit from it.
## QA:
coming soon
