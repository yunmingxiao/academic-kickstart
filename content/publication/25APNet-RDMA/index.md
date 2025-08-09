---
title: "Exposing RDMA NIC Resources for Software-Defined Scheduling"
authors:
- Yibo Huang
- Yiming Qiu
- Yunming Xiao
- Archit Bhatnagar
- Sylvia Ratnasamy
- Ang Chen
date: "2025-08-08T00:00:00Z"
doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-08T00:00:00Z"

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
publication: In *APNet'25* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *APNet'25*
note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Remote Direct Memory Access (RDMA) is emerging as a critical utility for large-scale datacenters, delivering significant performance improvements over the traditional TCP networking stack. Recent studies indicate that numerous applications can benefit from RDMA integration, and RDMA hardware resources are being shared among these diversifying applications. However, today’s RDMA frameworks mostly view their software and hardware stacks as two independent subsystems, making it difficult for developers to align the performance objectives of RDMA applications with the limited resources in RDMA hardware. 
<br><br>
We are developing a framework called SwiftRDMA, with the vision of enabling software-defined RDMA scheduling. SwiftRDMA views RDMA resource sharing as a scheduling problem. SwiftRDMA pinpoints the root causes of RDMA resource contentions and SLO violations, linking them to a set of trackable signals and controllable actions. A software scheduler then translates various operator demands into scheduling policies, which leverage the exposed signals and actions to achieve intended performance objectives. We describe our progress so far, and demonstrate the potential benefit of our approach. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: publication/25apnet-rdma/25apnet-rdma.pdf
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
