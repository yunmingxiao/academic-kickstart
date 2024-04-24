---
title: "De-Kodi: Understanding the Kodi Ecosystem"
authors:
- Marc Anthony Warrior
- Yunming Xiao
- Matteo Varvello
- Aleksandar Kuzmanovic
date: "2020-01-10T00:00:00Z"
doi: "10.1145/3366423.3380194"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-10T00:00:00Z"

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
publication: In Proceedings of *The World Wide Web Conference 2020*
publication_short: In *WWW'20*

abstract: Free and open source media centers are currently experiencing a boom in popularity for the convenience and flexibility they offer users seeking to remotely consume digital content. This newfound fame is matched by increasing notoriety — for their potential to serve as hubs for illegal content — and a presumably ever-increasing network footprint. It is fair to say that a complex ecosystem has developed around Kodi, composed of millions of users, thousands of “add-ons” – Kodi extensions from from 3rd-party developers – and content providers. Motivated by these observations, this paper aims at conducing the first analysis of the Kodi ecosystem. Our rationale is to build some “crawling” software around Kodi which can automatically install an addon, explore its menu, and locate (video) content. This is challenging for many reasons. First, Kodi largely relies on visual information and user input which intrinsically complicates automation. Second, no central aggregators for Kodi addons exist. Third, the potential sheer size of this ecosystem requires a highly scalable crawling solution. We address these challenges with de-Kodi, a full fledged crawling system capable of discovering and crawling large cross-sections of Kodi’s decentralized ecosystem at tunable levels of depth and breadth. With de-Kodi, we discovered and tested over 9,000 distinct Kodi addons. Our results demonstrate de-Kodi, which we make available to the general public, to be a essential asset in studying one of the largest multimedia platforms in the world. Our work further serves as the first ever transparent and repeatable analysis of the Kodi ecosystem at large.

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: https://safekodi.com/resource/dekodi.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://safekodi.com/resource/De-Kodi.mp4

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
