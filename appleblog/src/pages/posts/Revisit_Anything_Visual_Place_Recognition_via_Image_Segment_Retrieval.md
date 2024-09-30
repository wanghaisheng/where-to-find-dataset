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
- content: Kartik Garg et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-09-30 11:37:57'
tags:
- all search terms
- dataset
theme: light
title: Revisit Anything Visual Place Recognition via Image Segment Retrieval
---

# title: Revisit Anything Visual Place Recognition via Image Segment Retrieval 
## publish date: 
**2024-09-26** 
## authors: 
  Kartik Garg et.al. 
## paper id
2409.18049v1
## download
[2409.18049v1](http://arxiv.org/abs/2409.18049v1)
## abstracts:
Accurately recognizing a revisited place is crucial for embodied agents to localize and navigate. This requires visual representations to be distinct, despite strong variations in camera viewpoint and scene appearance. Existing visual place recognition pipelines encode the "whole" image and search for matches. This poses a fundamental challenge in matching two images of the same place captured from different camera viewpoints: "the similarity of what overlaps can be dominated by the dissimilarity of what does not overlap". We address this by encoding and searching for "image segments" instead of the whole images. We propose to use open-set image segmentation to decompose an image into `meaningful' entities (i.e., things and stuff). This enables us to create a novel image representation as a collection of multiple overlapping subgraphs connecting a segment with its neighboring segments, dubbed SuperSegment. Furthermore, to efficiently encode these SuperSegments into compact vector representations, we propose a novel factorized representation of feature aggregation. We show that retrieving these partial representations leads to significantly higher recognition recall than the typical whole image based retrieval. Our segments-based approach, dubbed SegVLAD, sets a new state-of-the-art in place recognition on a diverse selection of benchmark datasets, while being applicable to both generic and task-specialized image encoders. Finally, we demonstrate the potential of our method to ``revisit anything'' by evaluating our method on an object instance retrieval task, which bridges the two disparate areas of research: visual place recognition and object-goal navigation, through their common aim of recognizing goal objects specific to a place. Source code: https://github.com/AnyLoc/Revisit-Anything.
## QA:
coming soon
