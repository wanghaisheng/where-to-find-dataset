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
- content: Hanchen Wang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-10-14 11:37:30'
tags:
- all search terms
- dataset
theme: light
title: WaveDiffusion Exploring Full Waveform Inversion via Joint Diffusion in the
  Latent Space
---

# title: WaveDiffusion Exploring Full Waveform Inversion via Joint Diffusion in the Latent Space 
## publish date: 
**2024-10-11** 
## authors: 
  Hanchen Wang et.al. 
## paper id
2410.09002v1
## download
[2410.09002v1](http://arxiv.org/abs/2410.09002v1)
## abstracts:
Full Waveform Inversion (FWI) is a vital technique for reconstructing high-resolution subsurface velocity maps from seismic waveform data, governed by partial differential equations (PDEs) that model wave propagation. Traditional machine learning approaches typically map seismic data to velocity maps by encoding seismic waveforms into latent embeddings and decoding them into velocity maps. In this paper, we introduce a novel framework that reframes FWI as a joint diffusion process in a shared latent space, bridging seismic waveform data and velocity maps. Our approach has two key components: first, we merge the bottlenecks of two separate autoencoders-one for seismic data and one for velocity maps-into a unified latent space using vector quantization to establish a shared codebook. Second, we train a diffusion model in this latent space, enabling the simultaneous generation of seismic and velocity map pairs by sampling and denoising the latent representations, followed by decoding each modality with its respective decoder. Remarkably, our jointly generated seismic-velocity pairs approximately satisfy the governing PDE without any additional constraint, offering a new geometric interpretation of FWI. The diffusion process learns to score the latent space according to its deviation from the PDE, with higher scores representing smaller deviations from the true solutions. By following this diffusion process, the model traces a path from random initialization to a valid solution of the governing PDE. Our experiments on the OpenFWI dataset demonstrate that the generated seismic and velocity map pairs not only exhibit high fidelity and diversity but also adhere to the physical constraints imposed by the governing PDE.
## QA:
coming soon
