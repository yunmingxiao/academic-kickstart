---
title: "PreAcher: Secure and Practical Password Pre-Authentication by Content Delivery Networks"
authors:
- Shihan Lin
- Suting Chen
- Yunming Xiao
- Yanqi Gu
- Aleksandar Kuzmanovic
- Xiaowei Yang
date: "2025-04-28T01:00:00Z"
# doi: "10.1145/3627703.3629577"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-28T01:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *NSDI'25* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *NSDI'25*
# note: <b style='color:red;'>Best Student Paper Award!</b>

abstract: "In today's Internet, websites widely rely on password authentication for user logins. However, the intensive computation required for password authentication exposes web servers to Application-layer DoS (ADoS) attacks exploiting the login interfaces. Existing solutions fail to simultaneously prevent such ADoS attacks, preserve password secrecy, and maintain good usability. In this paper, we present PreAcher, a system architecture that incorporates third-party Content Delivery Networks (CDNs) into the password authentication process and offloads the authentication workload to CDNs without divulging the passwords to them. At the core of PreAcher is a novel three-party authentication protocol that combines Oblivious Pseudorandom Function (OPRF) and Locality-Sensitive Hashing (LSH). This protocol allows CDNs to pre-authenticate users and thus filter out ADoS traffic without compromising password security. Our evaluations demonstrate that PreAcher significantly enhances the resilience of web servers against both ADoS attacks and preserves password security while introducing acceptable overheads. Notably, PreAcher can be deployed immediately by websites alone today, without modifications to client software or CDN infrastructure. We release the source code of PreAcher to facilitate its deployment and future research. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/nsdi25/presentation/lin-shihan
url_pdf: publication/preacher/nsdi25-preacher.pdf
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
