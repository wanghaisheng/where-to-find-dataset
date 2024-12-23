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
- content: P. M. Chichura et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-12-23 11:35:37'
tags:
- all search terms
- dataset
theme: light
title: Pointing Accuracy Improvements for the South Pole Telescope with Machine Learning
---

# title: Pointing Accuracy Improvements for the South Pole Telescope with Machine Learning 
## publish date: 
**2024-12-19** 
## authors: 
  P. M. Chichura et.al. 
## paper id
2412.15167v1
## download
[2412.15167v1](http://arxiv.org/abs/2412.15167v1)
## abstracts:
We present improvements to the pointing accuracy of the South Pole Telescope (SPT) using machine learning. The ability of the SPT to point accurately at the sky is limited by its structural imperfections, which are impacted by the extreme weather at the South Pole. Pointing accuracy is particularly important during SPT participation in observing campaigns with the Event Horizon Telescope (EHT), which requires stricter accuracy than typical observations with the SPT. We compile a training dataset of historical observations of astronomical sources made with the SPT-3G and EHT receivers on the SPT. We train two XGBoost models to learn a mapping from current weather conditions to two telescope drive control arguments -- one which corrects for errors in azimuth and the other for errors in elevation. Our trained models achieve root mean squared errors on withheld test data of $2.14''$ in cross-elevation and $3.57''$ in elevation, well below our goal of $5''$ along each axis. We deploy our models on the telescope control system and perform further in situ test observations during the EHT observing campaign in 2024 April. Our models result in significantly improved pointing accuracy: for sources within the range of input variables where the models are best trained, average combined pointing error improved 33%, from $15.9''$ to $10.6''$. These improvements, while significant, fall shy of our ultimate goal, but they serve as a proof of concept for the development of future models. Planned upgrades to the EHT receiver on the SPT will necessitate even stricter pointing accuracy which will be achievable with our methods.
## QA:
coming soon
