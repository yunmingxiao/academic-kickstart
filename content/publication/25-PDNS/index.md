---
title: "Collusion Resistant DNS With Private Information Retrieval"
authors:
- Yunming Xiao
- Peizhi Liu
- Ruijie Yu
- Chenkai Weng
- Matteo Varvello
- Aleksandar Kuzmanovic
date: "2025-06-15T10:00:00Z"
doi: "10.48550/arXiv.2507.20806"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-15T10:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *ArXiv*

abstract: "There has been a growing interest in Internet user privacy, demonstrated by the popularity of privacy-preserving products such as Telegram and Brave, and the widespread adoption of HTTPS. The Domain Name System (DNS) is a key component of Internet-based communication and its privacy has been neglected for years. Recently, DNS over HTTPS (DoH) has improved the situation by fixing the issue of in-path middleboxes. Further progress has been made with proxy-based solutions such as Oblivious DoH (ODoH), which separate a user's identity from their DNS queries. However, these solutions rely on non-collusion assumptions between DNS resolvers and proxies -- an assumption difficult to guarantee in practice. To address this, we explore integrating single-server Private Information Retrieval (PIR) into DNS to enable encrypted query processing without relying on trust assumptions. However, applying PIR to DNS is challenging due to its hierarchical nature -- particularly, interactions with recursive resolvers can still leak information. Navigating performance and privacy trade-offs, we propose PDNS, a DNS extension leveraging single-server PIR to strengthen privacy guarantees. We have implemented a prototype of PDNS and compared its performance against state-of-the-art solutions via trace-driven experiments. The results show that PDNS achieves acceptable performance (2x faster than DoH over Tor with similar privacy guarantees) and strong privacy guarantees today, mainly at the cost of its scalability, which specialized hardware for PIR can address in the near future. "

tags:
#- 
featured: false

links:
- name: ArXiv
  url: https://arxiv.org/abs/2507.20806
url_pdf: publication/pdns/pdns-arxiv.pdf
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
