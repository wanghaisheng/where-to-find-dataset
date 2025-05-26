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
- content: Junfeng Wu et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-05-26 11:44:14'
tags:
- dataset
- all search terms
theme: light
title: TokBench Evaluating Your Visual Tokenizer before Visual Generation
---

# title: TokBench Evaluating Your Visual Tokenizer before Visual Generation 
## publish date: 
**2025-05-23** 
## authors: 
  Junfeng Wu et.al. 
## paper id
2505.18142v1
## download
[2505.18142v1](http://arxiv.org/abs/2505.18142v1)
## abstracts:
In this work, we reveal the limitations of visual tokenizers and VAEs in preserving fine-grained features, and propose a benchmark to evaluate reconstruction performance for two challenging visual contents: text and face. Image tokenization has significantly advanced visual generation and multimodal modeling, particularly with autoregressive models due to the modeling simplicity of discrete tokens. Autoregressive models typically rely on image tokenizers to compress images into discrete tokens for sequential prediction, whereas diffusion models often operate on continuous latent space to reduce computational costs. However, both visual compression approaches inevitably lose visual information, thereby limiting the upper bound of visual generation quality. To evaluate how these compression losses affect text and faces, the most human-sensitive visual elements, we first collect and curate a collection of text and faces images from existing datasets, ensuring clarity and diversity. For text reconstruction, we employ OCR models to assess the recognition accuracy of the reconstructed text, and then we measure feature similarity between original and reconstructed faces thereby quantifying faces reconstruction fidelity. Our method is highly lightweight, requiring just 2GB memory and 4 minutes to complete evaluations. With our benchmark, we analyze the reconstruction quality of text and faces at various scales across different image tokenizers and VAEs. Our results demonstrate that modern visual tokenizers still struggle to preserve fine-grained features, particularly at smaller scales. Furthermore, we extend this evaluation framework to the video, conducting a comprehensive analysis of video tokenizers. Additionally, we find that traditional metrics fail to accurately reflect the reconstruction performance for faces and text, while our proposed metrics serve as an effective complement.
## QA:
coming soon
