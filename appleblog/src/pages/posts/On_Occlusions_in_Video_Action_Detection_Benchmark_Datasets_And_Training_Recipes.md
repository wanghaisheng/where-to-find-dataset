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
- content: Rajat Modi et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-28 11:38:09'
tags:
- all search terms
- dataset
theme: light
title: On Occlusions in Video Action Detection Benchmark Datasets And Training Recipes
---

# title: On Occlusions in Video Action Detection Benchmark Datasets And Training Recipes 
## publish date: 
**2024-10-25** 
## authors: 
  Rajat Modi et.al. 
## paper id
2410.19553v1
## download
[2410.19553v1](http://arxiv.org/abs/2410.19553v1)
## abstracts:
This paper explores the impact of occlusions in video action detection. We facilitate this study by introducing five new benchmark datasets namely O-UCF and O-JHMDB consisting of synthetically controlled static/dynamic occlusions, OVIS-UCF and OVIS-JHMDB consisting of occlusions with realistic motions and Real-OUCF for occlusions in realistic-world scenarios. We formally confirm an intuitive expectation: existing models suffer a lot as occlusion severity is increased and exhibit different behaviours when occluders are static vs when they are moving. We discover several intriguing phenomenon emerging in neural nets: 1) transformers can naturally outperform CNN models which might have even used occlusion as a form of data augmentation during training 2) incorporating symbolic-components like capsules to such backbones allows them to bind to occluders never even seen during training and 3) Islands of agreement can emerge in realistic images/videos without instance-level supervision, distillation or contrastive-based objectives2(eg. video-textual training). Such emergent properties allow us to derive simple yet effective training recipes which lead to robust occlusion models inductively satisfying the first two stages of the binding mechanism (grouping/segregation). Models leveraging these recipes outperform existing video action-detectors under occlusion by 32.3% on O-UCF, 32.7% on O-JHMDB & 2.6% on Real-OUCF in terms of the vMAP metric. The code for this work has been released at https://github.com/rajatmodi62/OccludedActionBenchmark.
## QA:
coming soon
