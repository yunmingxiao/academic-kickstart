---
title: "TENSOR: Lightweight BGP Non-Stop Routing"
authors:
- Congcong Miao*
- Yunming Xiao*
- Marco Canini
- Ruiqiang Dai
- Shengli Zheng
- Jilong Wang
- Jiwu Bu
- Aleksandar Kuzmanovic
- Yachen Wang
date: "2023-05-17T10:00:00Z"
doi: "10.1145/3603269.3604852"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-17T10:00:00Z"

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
publication: In *SIGCOMM'23* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *SIGCOMM'23*

abstract: "As the solitary inter-domain protocol, BGP plays an important role in today’s Internet. Its failures threaten network stability and will usually result in large-scale packet losses. Thus, the non-stop routing (NSR) capability that protects inter-domain connectivity from being disrupted by various failures, is critical to any Autonomous System (AS) operator. Replicating the BGP and underlying TCP connection status is key to realizing NSR. But existing NSR solutions, which heavily rely on OS kernel modifications, have become impractical due to providers’ adoption of virtualized network gateways for better scalability and manageability.

In this paper, we tackle this problem by proposing TENSOR, which incorporates a novel kernel-modification-free replication design and lightweight architecture. More concretely, the kernel-modification-free replication design mitigates the reliance on OS kernel modification and hence allows the virtualization of the network gateway. Meanwhile, lightweight virtualization provides strong performance guarantees and improves system reliability. Moreover, TENSOR provides a solution to the split-brain problem that affects NSR solutions. Through extensive experiments, we show that TENSOR realizes NSR while bearing little overhead compared to open-source BGP implementations. Further, our two-year operational experience on a fleet of 400 servers controlling over 31,000 BGP peering connections demonstrates that TENSOR reduces the development, deployment, and maintenance costs significantly – at least by factors of 20, 5, and 10, respectively, while retaining the same SLA with the NSR-enabled routers. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: publication/tensor/tensor_sigcomm23.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'Tensor_sigcomm23.mp4'

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
