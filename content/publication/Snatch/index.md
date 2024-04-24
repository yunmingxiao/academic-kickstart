---
title: "Snatch: Online Streaming Analytics at the Network Edge"
authors:
- Yunming Xiao
- Yibo Zhao
- Sen Lin
- Aleksandar Kuzmanovic
date: "2024-01-01T10:00:00Z"
doi: "10.1145/3627703.3629577"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-11T10:00:00Z"

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
publication: In *EuroSys'24* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *EuroSys'24*
note: <b style='color:red;'>Best Student Paper Award!</b>

abstract: "In recent years, we have witnessed a growing trend of content hyper-giants deploying server infrastructure and services close to end-users, in “eyeball” networks. Still, one of the services that remained largely unaffected by this trend is online streaming analytics. This is despite the fact that most of the “big data” is received in real time and is most valuable at the time of arrival. The inability to process requests at the network edge is caused by a common setting where user profiles, necessary for analytics, are stored deep in the data center backends. This setting also carries privacy concerns as such user profiles are individually identifiable, yet the users are almost blind to what data is associated with their identities and how the data is analyzed. In this paper, we revise this arrangement, and plant encrypted semantic cookies at the user end. Without altering any of the existing protocols, this enables capturing and analytically pre-processing user requests soon after they are generated, at edge ISPs or content providers’ off-nets. In addition, it ensures user anonymity perseverance during the analytics. We design and implement Snatch, a QUIC-based streaming analytics prototype, and demonstrate that it speeds up user analytics by up to 200x, and by 10-30x in the common case. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3366423.3380194
url_pdf: publication/snatch/snatch-eurosys24-xiao.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/O0XLfwpqgTY

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
