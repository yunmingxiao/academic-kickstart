---
title: "Unlocking ECMP Programmability for Precise Traffic Control"
authors:
- Yadong Liu*
- Yunming Xiao*
- Xuan Zhang
- Weizhen Dang
- Huihui Liu
- Xiang Li
- Zekun He
- Jilong Wang
- Aleksandar Kuzmanovic
- Ang Chen
- Congcong Miao
date: "2024-12-11T00:00:00Z"
# doi: "10.1145/3627703.3629577"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-11T00:00:00Z"

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
publication: In *NSDI'25* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *NSDI'25*
# note: <b style='color:red;'>Best Student Paper Award!</b>

abstract: "ECMP (equal-cost multi-path) has become a fundamental mechanism in data centers, which distributes flows along multiple equivalent paths based on their hash values. Randomized distribution optimizes for the aggregate case, spreading load across flows over time. However, there exists a class of important Precise Traffic Control (PTC) tasks that are at odds with ECMP randomness. For instance, if an end host perceives that its flows are traversing a problematic switch/link, it often needs to change their paths before a fix can be rolled out. With randomized hashing, existing solutions resort to modifying flow tuples; since hashing mechanisms are unknown and they vary across switches/vendors, it may take many trials before yielding a new path. Many other similar cases exist where precise and timely response is critical to the network. We propose programmable ECMP (P-ECMP), a programming model, compiler, and runtime that provides precise traffic control. P-ECMP leverages an oft-ignored feature, ECMP groups, which allows for a constrained set of capabilities that are nonetheless sufficiently expressive for our tasks. An operator supplies high-level descriptions of their topology and policies, and our compiler generates PTC configurations for each switch. End hosts can reconfigure specific flows to use different PTC policies precisely and quickly, addressing a range of important use cases. We have evaluated P-ECMP using simulation at scale, and deployed one use case to a real-world data center that serves live user traffic. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/nsdi25/presentation/liu-yadong
url_pdf: publication/p-ecmp/nsdi25-pecmp.pdf
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
