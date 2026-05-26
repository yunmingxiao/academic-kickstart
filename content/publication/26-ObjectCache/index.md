---
title: "ObjectCache: Layerwise Object-Storage Retrieval for KV Cache Reuse"
authors:
- Yu Zhu
- Aditya Dhakal
- Yunming Xiao
- Dejan Milojicic
- Gustavo Alonso
date: "2026-04-21T00:00:00Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-21T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *ArXiv*
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Prefix KV caching has become a key mechanism in LLM serving: it reduces time to first token (TTFT) by avoiding redundant computation across requests that share a prefix (i.e., the system prompt). However, the accumulated KV cache is often larger than what GPU memory and local DRAM can hold. To preserve latency, current systems keep the KV cache in remote DRAM pools, increasing serving-cluster size and cost. In this paper, we explore a different approach: storing the KV cache in S3-compatible object storage so that capacity is no longer the constraint, while minimizing the impact on TTFT. We propose S3Cache, which co-designs the storage protocol and transfer schedule so that the storage server delivers KV cache data in the order the GPU consumes it, overlapping data transfer with compute across concurrent requests. We prototype S3Cache on a 100 Gbps RoCE cluster with NIXL (an inference library that abstracts storage and memory), Ceph RGW (an Object Gateway for clusters), and DAOS (an open source storage system). For 64K contexts, common in today's systems, S3Cache adds only 5.6% latency over local DRAM; for 4K contexts, where less compute is available to mask transfer, S3Cache adds 56--75,ms over the optimal local layerwise baseline. Under shared bandwidth caps, our scheduler reduces added TTFT by 1.2--1.8x compared with equal bandwidth sharing. "

tags:
#- 
featured: false

links:
- name: ArXiv
  url: https://arxiv.org/abs/2605.22850
# url_pdf: publication/26nsdi-ddos/nsdi26-xiao.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
# url_video: https://youtu.be/O0XLfwpqgTY

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example

---
