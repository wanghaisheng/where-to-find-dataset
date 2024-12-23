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
- content: Yang Tian et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-23 11:35:39'
tags:
- all search terms
- dataset
theme: light
title: Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation
---

# title: Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation 
## publish date: 
**2024-12-19** 
## authors: 
  Yang Tian et.al. 
## paper id
2412.15109v1
## download
[2412.15109v1](http://arxiv.org/abs/2412.15109v1)
## abstracts:
Current efforts to learn scalable policies in robotic manipulation primarily fall into two categories: one focuses on "action," which involves behavior cloning from extensive collections of robotic data, while the other emphasizes "vision," enhancing model generalization by pre-training representations or generative models, also referred to as world models, using large-scale visual datasets. This paper presents an end-to-end paradigm that predicts actions using inverse dynamics models conditioned on the robot's forecasted visual states, named Predictive Inverse Dynamics Models (PIDM). By closing the loop between vision and action, the end-to-end PIDM can be a better scalable action learner. In practice, we use Transformers to process both visual states and actions, naming the model Seer. It is initially pre-trained on large-scale robotic datasets, such as DROID, and can be adapted to realworld scenarios with a little fine-tuning data. Thanks to large-scale, end-to-end training and the synergy between vision and action, Seer significantly outperforms previous methods across both simulation and real-world experiments. It achieves improvements of 13% on the LIBERO-LONG benchmark, 21% on CALVIN ABC-D, and 43% in real-world tasks. Notably, Seer sets a new state-of-the-art on CALVIN ABC-D benchmark, achieving an average length of 4.28, and exhibits superior generalization for novel objects, lighting conditions, and environments under high-intensity disturbances on real-world scenarios. Code and models are publicly available at https://github.com/OpenRobotLab/Seer/.
## QA:
coming soon
