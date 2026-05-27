---
title: "Cost-effective and Reliable Global Internet Peering with Programmable Switches"
authors:
- Congcong Miao
- Zhiyi Yao
- Jianchao Lv
- Jinglin Wang
- Shihan Lin
- Xinyi Zhang
- Yunming Xiao
- Wei Guo
- Jiwu Bu
- Yachen Wang
- Marco Canini
- Gaogang Xie
date: "2026-04-15T00:00:00Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-15T00:00:00"

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
publication: In Proceedings of *23rd USENIX Symposium on Networked Systems Design and Implementation*. 
publication_short: NSDI'26
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Large-scale cloud providers always deploy peering routing system at the Internet’s peering edge to route traffic between the cloud and the Internet. Traditional router-based peering systems fail to pace up to the fast-changing application requirements, while the recent host-based approach is not cost-effective and struggles to address malicious traffic from the Internet. In this paper, we advocate for a radical new peering architecture to introduce programmable switches at the peering edge. We propose and implement a first-of-its-kind system, called Janus, to simultaneously handle inbound and outbound network traffic and significantly reduce network hardware cost. The core of Janus’s approach is to leverage a traffic dispatch module to offload most of the outbound traffic to switches to enhance system’s scalability. Janus offloads all inbound traffic to switches and redirects potential malicious traffic to the anti-DDoS service to enhance system reliability. Furthermore, Janus introduces a fast route convergence mechanism to effectively handle Internet-scale route updates. We have gradually deployed Janus at the edge of our production network over the past year. Evaluation results show that Janus can reduce the average hardware cost by 78%, as compared to existing systems while gracefully handling DDoS issues. Meanwhile, Janus can reduce the route convergence within seconds under failure scenarios, which is orders of magnitude faster than the existing approach. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/nsdi26/presentation/miao-peering
url_pdf: publication/26nsdi-peering/nsdi26-peering.pdf
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
