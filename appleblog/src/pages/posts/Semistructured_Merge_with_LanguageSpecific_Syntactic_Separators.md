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
- content: Guilherme Cavalcanti et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2024-07-29 11:32:44'
tags:
- dataset on github
- all search terms
theme: light
title: Semistructured Merge with LanguageSpecific Syntactic Separators
---

# title: Semistructured Merge with LanguageSpecific Syntactic Separators 
## publish date: 
**2024-07-26** 
## authors: 
  Guilherme Cavalcanti et.al. 
## paper id
2407.18888v1
## download
[2407.18888v1](http://arxiv.org/abs/2407.18888v1)
## abstracts:
Structured merge tools exploit programming language syntactic structure to enhance merge accuracy by reducing spurious conflicts reported by unstructured tools. By creating and handling full ASTs, structured tools are language-specific and harder to implement. They can also be computationally expensive when merging large files.To reduce these drawbacks, semistructured merge tools work with partial ASTs that use strings to represent lower level syntactic structures such as method bodies, and rely on unstructured tools to merge them. This, however, results in merge accuracy loss. To improve accuracy without compromising semistructured merge benefits, we propose a tool that leverages language-specific syntactic separators to infer structure without parsing. We still resort to an unstructured tool to merge lower level structures, but only after preprocessing the code so that text in between separators such as curly braces appear in separate lines. This way we emulate the capabilities of structured merge tools while avoiding their drawbacks. By comparing our tool with a robust implementation of semistructured merge, we find that our tool substantially reduces the number of spurious conflicts. We also observe significant but less substantial reductions on the overall number of reported conflicts, and of files with conflicts. However, similar to structured tools, our tool lets more merge conflicts go undetected. Our tool shows significant improvements over unstructured tools widely used in practice. Finally we observe that exploiting language-specific syntactic separators introduces unique textual alignment challenges.
## QA:
coming soon
