---
title: "Enabling Anonymous Online Streaming Analytics at the Network Edge"
authors:
- Yunming Xiao
- Yanqi Gu
- Yibo Zhao
- Sen Lin
- Aleksandar Kuzmanovic
date: "2025-06-16T10:00:00Z"
doi: "10.1145/3746130"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-16T10:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Computer Systems (TOCS)* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *ACM Transactions on Computer Systems (TOCS)*
# note: <b style='color:red;'>Best Student Paper Award!</b>

abstract: "In recent years, content hyper-giants have increasingly deployed server infrastructure and services close to end-users within \"eyeball\" networks. Still, online streaming analytics has largely remained unaffected by this trend. This is despite the fact that most of the “big data” is received in real-time and is most valuable at the time of arrival. The inability to process data at the network edge is caused by a common setting where user profiles, necessary for analytics, are stored deep in the data center back-ends. This setting also carries privacy concerns as such user profiles are individually identifiable, yet the users are almost blind to what data is associated with their identities and how the data is analyzed. In this paper, we revise this arrangement, and plant encrypted semantic cookies at the user end. By redesigning the cookie content without altering existing protocols, semantic cookies enable the capture and pre-processing of user data at edge ISPs or CDNs while preserving user anonymity. Additionally, lightweight cryptographic algorithms like partially homomorphic encryption can protect web providers' proprietary data from CDNs. We present Snatch, a QUIC-based streaming analytics prototype that achieves up to 200x faster user analytics, with common-case improvements of 10-30x. "

tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://dl.acm.org/doi/10.1145/3746130
url_pdf: publication/25tocs/25tocs-xiao.pdf
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
