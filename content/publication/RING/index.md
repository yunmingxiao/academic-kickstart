---
title: "Monetizing Spare Bandwidth: the Case of Distributed VPNs"
authors:
- Yunming Xiao
- Matteo Varvello
- Aleksandar Kuzmanovic
date: "2022-03-28T00:00:00Z"
doi: "10.1145/3530899"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication topic.
# Legend: 0 = Uncategorized; 1 = Undergraduate Projects; 2 = Security and Privacy;
# 3 = System Reliability; 4 = MLSys; 5 = Federated Learning; 
publication_topics: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *SIGMETRICS'22*

abstract: Residential Internet speeds have been rapidly increasing, reaching averages of ∼100 Mbps in most developed countries. Several studies have shown that users have way more bandwidth than they need, only using about 20-30% on a regular day. Several systems exploit this trend by enabling users to monetize their spare bandwidth, e.g., by sharing their WiFi connection or by participating in distributed proxy or VPN (dVPN) services. Despite the proliferation of such systems, little is known on how such marketplaces operate, what are the key factors that determine the price of the spare bandwidth, and how such prices differ worldwide. In this work, we shed some light on this topic using dVPNs as a use-case. We start by formalizing the problem of bandwidth monetization as an optimization between a buyer’s cost and seller’s income. Next, we explore three popular dVPNs (Mysterium, Sentinel, and Tachyon) using both active and passive measurements. We find that dVPNs have a large and growing footprint, and offer comparable performance to their centralized counterpart. We identify Mysterium (in the US) as the most concrete realization of a bandwidth marketplace, for which we derive a value of spare Internet bandwidth ranging between 11 and 14 cents per GB. We also show that both buyers and sellers utilize ad-hoc “rules-of-thumb” when choosing their prices, which results in a sub-optimal marketplace. By applying our optimization, a seller’s income can be tripled by setting a price lower than the default one which allows to attract more buyers. These observations motivate us to create RING, a first and concrete system which helps sellers to automatically adjust their prices and traffic volumes across multiple marketplaces. 

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3530899
# url_pdf: https://safekodi.com/resource/dekodi.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/pBSuyBAOOTc

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
