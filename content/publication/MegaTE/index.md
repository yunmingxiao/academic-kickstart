---
title: "MegaTE: Extending WAN Traffic Engineering to Millions of Endpoints in Virtualized Cloud"
authors:
- Congcong Miao*
- Zhizhen Zhong*
- Yunming Xiao*
- Feng Yang*
- Senkuo Zhang*
- Chaodong Lu
- Jingyi Geng
- Yachen Wang
- Xianneng Zou
- Yinan Jiang
- Zizhuo Bai
- Chuanchuan Yang

date: "2024-06-03T10:00:00Z"
doi: "10.1145/3651890.3672242"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-03T10:00:00Z"

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
publication: In ACM *SIGCOMM'24* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *SIGCOMM'24*

abstract: "In today’s virtualized cloud, containers and virtual machines (VMs)
are prevailing methods to deploy applications with different tenant
requirements. However, these requirements are at odds with the
resource allocation capabilities of conventional networking stacks
in wide-area networks (WANs). In particular, existing WAN traffic
engineering (TE) systems, focused on optimizing link utilization
and minimizing congestion at the granularity of aggregated traffic
flows, are not designed to cater to each individual flow. In this paper,
we advocate for a radical new approach to extend TE systems
to involve millions of virtual instance endpoints. We propose and
implement a first-of-its-kind system, called MegaTE, to satisfy the
needs of each fine-grained traffic flow at the virtual instance level.
At the core of the MegaTE system is the paradigm shift from the
top-down centralized control to the bottom-up asynchronous query
in the TE control loop, combined with eBPF-based segment routing
on the data plane and TE optimization contraction on the control
plane. We evaluate MegaTE using flow-level simulations with production
traffic traces. Our results show that MegaTE supports 20×
more endpoints with the similar algorithm run time compared to
prior work. MegaTE has been adopted by large-scale public cloud
providers. Notably, Tencent rolled out MegaTE in its cloud WAN
since December 2022. Our production analysis shows that MegaTE
reduces the packet latency of real-time applications by up to 51%. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3651890.3672242
url_pdf: publication/megate/sigcomm24-megate.pdf
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
