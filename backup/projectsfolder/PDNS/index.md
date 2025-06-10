---
title: "PDNS: A Fully Privacy-Preserving DNS"
summary: We propose PDNS which uses Private Information Retrieval to allow DNS resolvers to operate on encrypted DNS queries, thereby eliminating any privacy leaks.
tags:
#- Deep Learning
date: "2023-07-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: "https://safekodi.com"

image:
  caption: PDNS Overview
  focal_point: ""
  preview_only: false

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

There has been a growing interest in Internet user privacy, demonstrated by the popularity of privacy-preserving products such as Telegram and Brave, and the widespread adoption of HTTPS. The Domain Name System (DNS) is a key component of Internet-based communication and its privacy has been neglected for years. Recently, DNS over HTTPS (DoH) has improved the situation by fixing the issue of in-path middleboxes. Further progress has been made with proxy-based solutions such as Oblivious DoH (ODoH) and DoH over Tor (DoHoT), which separate a user’s identity from their DNS queries. However, these solutions rely on trusted DNS resolvers and non-collusion with the proxy network. This paper proposes a new extension to DNS, called PDNS, that uses Private Information Retrieval to allow DNS resolvers to operate on encrypted DNS queries, thereby eliminating any privacy leaks. We have implemented a prototype of PDNS and compared its performance against all state-of-the-art solutions via trace-driven experiments. The results show that PDNS achieves high performance and strong privacy guarantees, mainly at the cost of its scalability, which specialized hardware for PIR can address in the near future.

<!-- <br>
<h3>Resources</h3>
<a href="https://ringdvpn.com/">RING: The first multi-vendors bandwidth marketplace</a> -->
<br>
<h3>Demo</h3>
Yunming Xiao, Chenkai Weng, Ruijie Yu, Peizhi Liu, Matteo Varvello, Aleksandar Kuzmanovic (2023). <a href="demo_pdns.pdf">Demo: PDNS: A Fully Privacy-Preserving DNS</a>. In SIGCOMM'23. <a href="poster_pdns.pdf">[Poster PDF]</a>
<br>
<h3>Publication</h3>
TBA
<!-- Yunming Xiao, Matteo Varvello (2022). <a href="../../publication/fiat/">FIAT: Frictionless Authentication of IoT Traffic</a>. In CoNEXT'22. -->
<!-- <br>
<h3>Technical Report</h3>
Yunming Xiao, Matteo Varvello (2021). <a href="../../files/frictionless.pdf">FIAT: Frictionless Authentication of IoT Traffic</a>. 
<br> -->
<!-- <h3>Publications</h3>
... -->
<!-- 1. Marc Anthony Warrior, Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2020). <a href="../../publication/dekodi/">De-Kodi: Understanding the Kodi Ecosystem</a>. In WWW’20. -->
