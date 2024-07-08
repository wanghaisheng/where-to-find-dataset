---
layout: '../../layouts/MarkdownPost.astro'
title: '**Streaming Large-Scale Electron Microscopy Data to a Supercomputing Facility**'
pubDate: '2024-07-09 06:20:28'
description: ''
author: 'wanghaisheng'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/product/homepod/standard/Apple-HomePod-hero-230118_big.jpg.large_2x.jpg'
    alt: 'cover'
tags: '['all search terms']' 
theme: 'light'
featured: true

meta:
 - name: author
   content: Samuel S. Welborn et.al.
 - name: keywords
   content: key3, key4

keywords: key1, key2, key3
---

## paper id
2407.03215v1
## download
[2407.03215v1](http://arxiv.org/abs/2407.03215v1)
## abstracts:
Data management is a critical component of modern experimental workflows. As data generation rates increase, transferring data from acquisition servers to processing servers via conventional file-based methods is becoming increasingly impractical. The 4D Camera at the National Center for Electron Microscopy (NCEM) generates data at a nominal rate of 480 Gbit/s (87,000 frames/s) producing a 700 GB dataset in fifteen seconds. To address the challenges associated with storing and processing such quantities of data, we developed a streaming workflow that utilizes a high-speed network to connect the 4D Camera's data acquisition (DAQ) system to supercomputing nodes at the National Energy Research Scientific Computing Center (NERSC), bypassing intermediate file storage entirely. In this work, we demonstrate the effectiveness of our streaming pipeline in a production setting through an hour-long experiment that generated over 10 TB of raw data, yielding high-quality datasets suitable for advanced analyses. Additionally, we compare the efficacy of this streaming workflow against the conventional file-transfer workflow by conducting a post-mortem analysis on historical data from experiments performed by real users. Our findings show that the streaming workflow significantly improves data turnaround time, enables real-time decision-making, and minimizes the potential for human error by eliminating manual user interactions.
## QA:
coming soon
