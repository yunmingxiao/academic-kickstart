---
title: "Conspirator: SmartNIC-Aided Control Plane for Distributed ML Workloads"
authors:
- Yunming Xiao
- Diman Zad Tootaghaj
- Aditya Dhakal
- Lianjie Cao
- Puneet Sharma
- Aleksandar Kuzmanovic
date: "2024-06-03T10:00:00Z"
# doi: "10.1145/3627703.3629577"

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
publication_topics: ["2"]

# Publication name and optional abbreviated publication name.
publication: In USENIX *ATC'24* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *ATC'24*

abstract: "Modern machine learning (ML) workloads heavily depend on distributing tasks across clusters of server CPUs and specialized accelerators, such as GPUs and TPUs, to achieve optimal performance. Nonetheless, prior research has highlighted the inefficient utilization of computing resources in distributed ML, leading to suboptimal performance. This inefficiency primarily stems from CPU bottlenecks and suboptimal accelerator scheduling. Although numerous proposals have been put forward to address these issues individually, none have effectively tackled both inefficiencies simultaneously. In this paper, we introduce Conspirator, an innovative control plane design aimed at alleviating both bottlenecks by harnessing the enhanced computing capabilities of SmartNICs. Following the evolving role of SmartNICs, which have transitioned from their initial function of standard networking task offloading to serving as programmable connectors between disaggregated computing resources, Conspirator facilitates efficient data transfer without the involvement of host CPUs and hence circumvents the potential bottlenecks there. Conspirator further integrates a novel scheduling algorithm that takes into consideration of the heterogeneity of accelerators and adapts to changing workload dynamics, enabling the flexibility to mitigate the second bottleneck. Our evaluation demonstrates that Conspirator may provide a 15% end-to-end completion time reduction compared to RDMA-based alternatives while being 17% more cost-effective and 44% more power-efficient. Our proposed scheduler also helps to save 33% GPU hours compared to naive GPU-sharing schedulers by making close-to-optimal decisions while taking much less time than the optimal NP-Hard scheduler. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/atc24/presentation/xiao
url_pdf: publication/conspirator/atc24-xiao.pdf
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
