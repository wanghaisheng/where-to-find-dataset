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
- content: Eric Qu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-11-04 11:37:40'
tags:
- all search terms
- dataset
theme: light
title: The Importance of Being Scalable Improving the Speed and Accuracy of Neural
  Network Interatomic Potentials Across Chemical Domains
---

# title: The Importance of Being Scalable Improving the Speed and Accuracy of Neural Network Interatomic Potentials Across Chemical Domains 
## publish date: 
**2024-10-31** 
## authors: 
  Eric Qu et.al. 
## paper id
2410.24169v1
## download
[2410.24169v1](http://arxiv.org/abs/2410.24169v1)
## abstracts:
Scaling has been critical in improving model performance and generalization in machine learning. It involves how a model's performance changes with increases in model size or input data, as well as how efficiently computational resources are utilized to support this growth. Despite successes in other areas, the study of scaling in Neural Network Interatomic Potentials (NNIPs) remains limited. NNIPs act as surrogate models for ab initio quantum mechanical calculations. The dominant paradigm here is to incorporate many physical domain constraints into the model, such as rotational equivariance. We contend that these complex constraints inhibit the scaling ability of NNIPs, and are likely to lead to performance plateaus in the long run. In this work, we take an alternative approach and start by systematically studying NNIP scaling strategies. Our findings indicate that scaling the model through attention mechanisms is efficient and improves model expressivity. These insights motivate us to develop an NNIP architecture designed for scalability: the Efficiently Scaled Attention Interatomic Potential (EScAIP). EScAIP leverages a multi-head self-attention formulation within graph neural networks, applying attention at the neighbor-level representations. Implemented with highly-optimized attention GPU kernels, EScAIP achieves substantial gains in efficiency--at least 10x faster inference, 5x less memory usage--compared to existing NNIPs. EScAIP also achieves state-of-the-art performance on a wide range of datasets including catalysts (OC20 and OC22), molecules (SPICE), and materials (MPTrj). We emphasize that our approach should be thought of as a philosophy rather than a specific model, representing a proof-of-concept for developing general-purpose NNIPs that achieve better expressivity through scaling, and continue to scale efficiently with increased computational resources and training data.
## QA:
coming soon