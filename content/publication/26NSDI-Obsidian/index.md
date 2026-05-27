---
title: "Secure Vickrey Auctions for Online Advertising"
authors:
- Archit Bhatnagar
- Yunming Xiao
- Ang Chen
- Amrita Roy Chowdhury
date: "2026-04-15T00:00:01Z"
# doi: "10.1145/3735358.3735359"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-15T00:00:01"

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
publication: In Proceedings of *23rd USENIX Symposium on Networked Systems Design and Implementation*. 2026. 
publication_short: NSDI'26
# note: <b style='color:red;'>Best Paper Award!</b>

abstract: "Online advertising is an essential part of the web ecosystem. When a user's browser lands on a webpage, advertisers bid for the ad space on the webpage. An auction algorithm (e.g., Vickrey/second-price auction) is executed to determine the winner and the price---ideally, only this information is revealed, and everything else (i.e., the losing bids and the bidder identities) is kept private. However, achieving these privacy goals under a malicious security model, while operating under stringent performance requirements, is challenging. 
<br><br>
We propose Obsidian, which enables secure Vickrey auctions with three ideas: a new MPC-friendly encoding scheme that decouples bid values from bidders' identities; a novel use of function secret sharing to shift the cost of encoding validation to an offline phase; and a lightweight ring signature scheme to anonymously verify bidders. We show that Obsidian significantly outperforms generic MPC and homomorphic encryption approaches—by orders of magnitude—and even surpasses Addax, a system tailored to ad auctions, despite Addax assuming a weaker (covert) threat model and leaking more information. "

tags:
#- 
featured: false

links:
- name: USENIX
  url: https://www.usenix.org/conference/nsdi26/presentation/bhatnagar
url_pdf: publication/26nsdi-obsidian/nsdi26-secure-auction.pdf
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
