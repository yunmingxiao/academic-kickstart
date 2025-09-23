---
title: "An RDMA-First Object Storage System with SmartNIC Offload"
authors:
- Yu Zhu
- Aditya Dhakal
- Pedro Bruel
- Gourav Rattihalli
- Yunming Xiao
- Johann Lombardi
- Dejan Milojicic
date: "2025-09-10T10:00:00Z"
# doi: "10.48550/arXiv.2505.19025" 

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-10T10:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = Cloud Infra; 2 = Uncategorized; 
# 3 = Undergraduate Projects
publication_topics: ["1"]

# Publication name and optional abbreviated publication name.
publication: To appear in *RESDIS@SC* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: To appear in *RESDIS@SC*

abstract: "AI training and inference impose sustained, fine-grained I/O that stresses host-mediated, TCP-based storage paths. We revisit POSIX-compatible object storage for GPU-centric pipelines and present ROS2, an RDMA-first design that offloads the DAOS client to an NVIDIA BlueField-3 SmartNIC while leaving the server-side DAOS I/O engine unchanged. ROS2 splits a lightweight gRPC control plane from a high-throughput data plane (UCX/libfabric over RDMA or TCP), removing host mediation from the data path. Using FIO/DFS across local and remote settings, we show that on server-grade CPUs RDMA consistently outperforms TCP for large sequential and small random I/O. When the client is offloaded to BlueField-3, RDMA performance matches the host; TCP on the SmartNIC lags, underscoring RDMA’s advantage for offloaded deployments. We conclude that an RDMA-first, SmartNIC-offloaded object store is a practical foundation for LLM data delivery; optional GPUDirect placement is left for future work. "

tags:
#- 
featured: false

links:
- name: ArXiv
  url: https://arxiv.org/abs/2509.13997
url_pdf: publication/25resdis-sc/2509.13997v1.pdf
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
