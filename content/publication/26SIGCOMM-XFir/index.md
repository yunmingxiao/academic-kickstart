---
title: "XFir: Accelerating New-Flow Setup on Host Servers of a Large Cloud Network"
authors:
- Shihan Lin
- Shunqiao Jiang
- Liang Wang
- Jian Wang
- Chao Pei
- Jian Zhao
- Wenjun Wu
- Kai Ren
- Lijun Zhuang
- Qingmin Liu
- Heng Yu
- Sirui Li
- Yibo Huang
- Yifei Zhu
- Yunming Xiao
- Linghe Kong
date: "2026-05-12T00:00:01Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-12T00:00:01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["1"]

# Publication name and optional abbreviated publication name.
publication: To appear in *SIGCOMM'26* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: To appear in *SIGCOMM'26*
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "In today's cloud networks, host servers widely deploy Data Processing Units (DPUs) as network accelerators under the ``Sep-Path'' paradigm. However, as server capabilities scale with increasing CPU cores and network bandwidth, the software slow path (executed on a DPU's CPU) has become a critical bottleneck for workloads with high new-flow rates. Meanwhile, new-flow setup logic on host servers must continuously evolve to meet diverse and changing customer demands, making flexibility a key requirement alongside performance. To address this gap, we present XFir, the first hardware-accelerated new-flow setup system for cloud host servers that delivers high CPS throughput while preserving sufficient flexibility. XFir leverages a next-generation DPU equipped with a Cloud Network co-Processor (CNP) to execute the host server's new-flow setup logic. XFir redesigns the host-server flow-setup datapath and table layout, optimizes LPM lookups, and introduces CPU–CNP collaboration mechanisms to further improve performance and reliability. Our evaluation shows that XFir achieves over 776K new-flow CPS on a single host server with 11.7μs slow-path latency. Compared to prior work (Fornax), XFir achieves 4.8×CPS and reduces latency by 69.2%. Moreover, XFir is cost-effective to deploy in production, requiring only a single DPU per host. Overall, XFir improves new-flow throughput while maintaining development flexibility at low financial cost. "

tags:
#- 
featured: false

links:
# - name: USENIX
#   url: https://www.usenix.org/conference/nsdi26/presentation/xiao
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
