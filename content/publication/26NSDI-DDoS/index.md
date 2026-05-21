---
title: "DDoS Detection at the Scale of One Hundred Tbps"
authors:
- Yunming Xiao
- Xijun Luo
- Youliang Jiang
- Aike Wang
- Hu Chen
- Zhibin Zhou
- Heng Yu
- Jiahao Cao
- Yong Jiang
- Jilong Wang
- Mingwei Xu
- Yan Chen
- Congcong Miao
date: "2026-04-15T00:00:02Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-15T00:00:02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["0", "1"]

# Publication name and optional abbreviated publication name.
publication: In *NSDI'26* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *NSDI'26*
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Defending against Distributed Denial-of-Service (DDoS) attacks is a critical priority for cloud providers, who must manage ever-growing volumes of both benign and malicious traffic. While state-of-the-art DDoS detection systems leverage programmable devices to process traffic at hundreds of Gbps to Tbps on a single machine, large-scale cloud providers often handle traffic at scales approaching 100 Tbps. This massive volume -- two orders of magnitude higher than the traffic handled by existing systems -- motivates us to implement distributed processing across multiple servers, where new challenges are present. Specifically, naive load-balancing strategies lead to imbalanced traffic distribution and severe performance bottlenecks, while function offloading to programmable devices must balance flexibility and adaptability. In this paper, we present Canopy, a scalable DDoS detection system designed to overcome these challenges. Canopy features a dynamic load-balancing mechanism that adapts to fluctuating traffic patterns, ensuring balanced distribution across detection servers despite the mix of mice and elephant flows. Additionally, it employs a traffic compression technique at the programmable switch to significantly reduce per-server workload. These innovations enable Canopy to scale to over 100,Tbps in real-world deployments. Successfully deployed in production, Canopy has demonstrated its effectiveness in mitigating large-scale DDoS attacks. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/nsdi26/presentation/xiao
url_pdf: publication/26nsdi-ddos/nsdi26-xiao.pdf
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
