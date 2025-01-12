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
- content: Isaac Zhang et.al.
  name: author
- content: key3, key4
  name: keywords
pubDate: '2025-01-12 17:17:16'
tags:
- dataset
- all search terms
theme: light
title: QMDB Quick Merkle Database
---

# title: QMDB Quick Merkle Database 
## publish date: 
**2025-01-09** 
## authors: 
  Isaac Zhang et.al. 
## paper id
2501.05262v1
## download
[2501.05262v1](http://arxiv.org/abs/2501.05262v1)
## abstracts:
Updating, managing, and proving world state are key bottlenecks facing the execution layer of blockchains today. Existing storage solutions are not flash-optimized and suffer from high flash write amplification and excessive DRAM requirements, forcing a trade-off between throughput and decentralization. We present the Quick Merkle Database (QMDB), an SSD-optimized authenticated data structure that delivers a superset of the features of existing databases. QMDB's append-only design enables 1 SSD read per state access, $O(1)$ I/Os for updates, and in-memory Merkleization on a DRAM footprint small enough to fit on consumer-grade PCs. We demonstrate that QMDB offers a significant leap in throughput ($6 \times$ over RocksDB and $8 \times$ over a state-of-the-art verifiable database) and validate its scalability on datasets up to 15 billion entries ($10 \times$ Ethereum's state size in 2024). Our projections indicate QMDB could store a theoretical maximum of 280 billion entries on a single machine, far exceeding current blockchain requirements. QMDB scales across both commodity and enterprise hardware, achieving up to 2 million state updates per second. QMDB sets a new benchmark for verifiable databases, alleviating today's storage bottlenecks, lowering barriers to blockchain participation, and unlocking new blockchain applications.
## QA:
coming soon
