---
title: "RAG on the Decentralized Web: An Empirical Study of Akash and Golem"
authors:
- Suting Chen
- Matteo Varvello
- Aleksandar Kuzmanovic
- Yunming Xiao
date: "2026-04-22T00:00:00Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-22T00:00:00Z"

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
publication: To appear in Proceedings of *the 10th Asia-Pacific Workshop on Networking*. 
publication_short: APNet'26
pub_badge_normal: true
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Decentralized compute markets claim to be an alternative to the cloud, yet the systems community lacks hard evidence on whether they can run modern workloads end to end. We put this claim to the test by deploying a Retrieval-Augmented Generation (RAG) pipeline on the Akash and Golem networks. Our analysis reveals a striking paradox: supply is abundant, with over 10,000 CPU cores and 50~TiB of memory available, yet utilization remains minimal (about 0.3% on Akash). When mapped carefully, several RAG pipeline stages execute correctly and up to 3x cheaper than AWS. Others degrade under node churn and network bottlenecks. The limiting factor is not raw capacity but predictability. We also observe that decentralization in practice is already hybrid, with centralized gateways and offchain services masking blockchain complexity. Taken together, our findings suggest that decentralized markets are neither hype nor drop-in cloud replacements, but an underutilized substrate whose viability depends on better scheduling, reliability mechanisms, and trust primitives. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
# url_pdf: publication/25apnet-rdma/25apnet-rdma.pdf
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
