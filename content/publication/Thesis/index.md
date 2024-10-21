---
title: "Revising System Premises For a Secure and Private Web"
authors:
- Yunming Xiao
date: "2024-05-03T10:00:00Z"
# doi: "10.1145/3627703.3629577"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-03T10:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
# publication_topics: ["0"]

# Publication name and optional abbreviated publication name.
publication: Ph.D. Thesis #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: Ph.D. Thesis

abstract: "As residential bandwidth continues to grow and people become increasingly dependent on the Internet, previously overlooked security and privacy issues have become severe threats to Internet users, raising public concerns. These threats are numerous and far-reaching, spanning across various network or system layers, as well as different applications and services. Despite the considerable efforts made, the current situation is still far from ideal, mainly because of the continuously evolving security and privacy demands, as well as the rapid development of countermeasures.


This thesis aims to examine the security and privacy vulnerabilities in the current Web components and present appropriate solutions to address them. My approach is to develop practical cutting-edge network systems that enhance security and privacy without compromising on efficiency. To achieve this objective, I undertake comprehensive evaluations to gain insights into the current systems, and suggest enhancements through revising the key system premises that contribute to the vulnerabilities. Such revisions facilitate the mitigation of vulnerabilities and allow the incorporation of new system pieces, e.g., advanced cryptographic tools. The resulting system should also provide satisfactory performance and be feasible to be deployed today.


In this thesis, I begin by examining one general concept for securing any network system - the virtual private network (VPN). Specifically, I concentrate on decentralized VPN (DVPN), a recent system revision proposal that improves user privacy by distributing VPN proxies to multiple parties, making it challenging for anyone to retrieve information about users and connections. Nonetheless, my analysis reveals that DVPN fails to provide adequate security and privacy guarantees due to the reliance on trust placed in the proxies. 


Unfortunately, relieving such trust dependencies in a proxy-based system proves to be a formidable task. Hence, I pivot to directly enhancing the specific Internet services and applications themselves. My first target is the domain name service (DNS), a fundamental Internet service behind almost any wild-area network requests. Through careful scrutinization of existing proposals, I find that the presence of recursive resolvers is the key system premise that contribute to the current DNS privacy vulnerabilities. DNS privacy can be substantially improved by having the recursive resolvers operate in blind, i.e., answering the queries without knowing their contents. While this sounds counter-intuitive, it can actually be realized through advanced cryptography tools named private information retrieval (PIR). Following this direction, I build PDNS, an efficient and practical DNS system based on PIR. Thorough evaluations demonstrate that PDNS achieves acceptable performance as of today and offers better privacy preservation than any state-of-the-art proposals.


PDNS cannot safeguard the interconnected and multi-layered Internet alone. Indeed, user privacy exposure at one component negates protective measures at other components. With this in mind, I proceed to investigate another vital Internet component, the Hypertext Transfer Protocol (HTTP) -- the bedrock of the Web -- where I identify an instance of such a privacy violation. Specifically, Web providers are harvesting user information through HTTP cookies. The root cause is that current cookies are semantically oblivious, i.e., they carry personally identifiable information (PII) but lack useful information for analytics. To solve this issue, I revise the system premises and propose semantic cookies -- cookies discarding any PII. Evaluations show that semantic cookies not only patch up privacy leakage in HTTP requests but also accelerate cookie analytics by exploiting edge infrastructures, providing incentives for adoption. This exemplifies my system design philosophy of achieving balance among performance, security/privacy guarantees, and practicality.
"

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: publication/thesis/Yunming-PhD-Thesis.pdf
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
