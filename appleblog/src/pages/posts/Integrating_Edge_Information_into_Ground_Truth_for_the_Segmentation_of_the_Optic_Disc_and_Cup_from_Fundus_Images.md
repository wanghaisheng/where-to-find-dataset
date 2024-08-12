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
- content: Yoga Sri Varshan V et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-08-12 11:32:48'
tags:
- dataset
- all search terms
theme: light
title: Integrating Edge Information into Ground Truth for the Segmentation of the
  Optic Disc and Cup from Fundus Images
---

# title: Integrating Edge Information into Ground Truth for the Segmentation of the Optic Disc and Cup from Fundus Images 
## publish date: 
**2024-08-09** 
## authors: 
  Yoga Sri Varshan V et.al. 
## paper id
2408.05052v1
## download
[2408.05052v1](http://arxiv.org/abs/2408.05052v1)
## abstracts:
Optic disc and cup segmentation helps in the diagnosis of glaucoma, myocardial infarction, and diabetic retinopathy. Most deep learning methods developed to perform segmentation tasks are built on top of a U-Net-based model architecture. Nevertheless, U-Net and its variants have a tendency to over-segment/ under-segment the required regions of interest. Since the most important outcome is the value of cup-to-disc ratio and not the segmented regions themselves, we are more concerned about the boundaries rather than the regions under the boundaries. This makes learning edges important as compared to learning the regions. In the proposed work, the authors aim to extract both edges of the optic disc and cup from the ground truth using a Laplacian filter. Next, edges are reconstructed to obtain an edge ground truth in addition to the optic disc-cup ground truth. Utilizing both ground truths, the authors study several U-Net and its variant architectures with and without optic disc and cup edges as target, along with the optic disc-cup ground truth for segmentation. The authors have used the REFUGE benchmark dataset and the Drishti-GS dataset to perform the study, and the results are tabulated for the dice and the Hausdorff distance metrics. In the case of the REFUGE dataset, the optic disc mean dice score has improved from 0.7425 to 0.8859 while the mean Hausdorff distance has reduced from 6.5810 to 3.0540 for the baseline U-Net model. Similarly, the optic cup mean dice score has improved from 0.6970 to 0.8639 while the mean Hausdorff distance has reduced from 5.2340 to 2.6323 for the same model. Similar improvement has been observed for the Drishti-GS dataset as well. Compared to the baseline U-Net and its variants (i.e) the Attention U-Net and the U-Net++, the models that learn integrated edges along with the optic disc and cup regions performed well in both validation and testing datasets.
## QA:
coming soon
