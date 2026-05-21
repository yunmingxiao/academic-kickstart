---
title: "CubeTrace: Microscopic Network Tracing for Heterogeneous Cloud Gateways"
authors:
- Yunming Xiao
- Yinchao Yang
- Jiaqi Zheng
- Xuqian Li
- Dongbo Gu
- Chao Pei
- Chen Tian
- Mingwei Xu
- Ang Chen
- Congcong Miao
date: "2026-05-12T00:00:02Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-12T00:00:02"

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

abstract: "Modern cloud gateways have evolved to include diverse network functions and heterogeneous hardware, such as programmable switches and FPGAs, to handle increasing workloads and minimize forwarding latency. However, existing network tracing tools are limited to device-level data collection, lacking the granularity required to ensure reliability in these complex architectures. For instance, they fail to pinpoint which function on which hardware component is responsible for packet losses or latency spikes. To bridge this gap, we present CubeTrace, a unified, function-level flow tracing system that enables microscopic tracing inside heterogeneous cloud gateways. CubeTrace standardizes tracing units as \"cubes\" across different hardware platforms, regardless of their varied underlying implementations, and operates at flow-level granularity instead of packet level for reliability reasons. This creates a new tracing abstraction that satisfies the complex tracing demands of heterogeneous cloud gateways while maintaining high efficiency. Moreover, flow-cube data can be decoded into packet-level representations and integrated with well-established distributed tracing frameworks, enabling the use of off-the-shelf analysis tools. Our evaluations demonstrate that CubeTrace introduces minimal overhead, consuming less than 1% of memory resources and adding less than 1% to forwarding latency. Having been deployed in a large-scale cloud gateway, CubeTrace has significantly improved problem localization, reducing resolution times from hours or even days to just minutes. "

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
