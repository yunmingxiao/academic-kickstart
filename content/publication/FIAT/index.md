---
title: "FIAT: Frictionless Authentication of IoT Traffic"
authors:
- Yunming Xiao
- Matteo Varvello
date: "2022-10-16T10:00:00Z"
doi: "10.1145/3555050.3569126"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-06T10:00:00Z"

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
publication: In Proceedings of the *CoNEXT'22* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *CoNEXT'22*

abstract: "Home IoT (Internet of Things) deployments are vulnerable to local adversaries, compromising a LAN, and remote adversaries, compromising either the accounts associated with IoT devices or third-party devices like mobile phones used to control the IoT. There is, however, a fundamental difference between an attacker and a legitimate IoT user: the physical interaction with the device (e.g., via a mobile app) used to operate the IoT. Such physical interactions can be used to build frictionless authentications. However, their integration with IoT requires each vendor to independently adopt them, which is both complex and expensive. We instead design and build FIAT, the first third-party mechanism to automatically authorize IoT traffic by learning recurring traffic and validating human actions behind unpredictable traffic. FIAT does not require modification of the IoT devices or apps, as it operates passively on network traffic. Our evaluation shows that FIAT achieves high accuracy with minimal impact on the user experience. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: publication/fiat/conext22-xiao.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: 'fiat_conext22.mp4'

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
