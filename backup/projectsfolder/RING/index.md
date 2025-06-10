---
title: A First Look Into Distributed VPNs
summary: We perform the first comprehensive measurement to the emerging distributed VPN networks.
tags:
#- Deep Learning
date: "2021-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: "https://safekodi.com"

image:
  caption: RING
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

Ookla reported that average Internet speeds in American homes grew 20x in the last 10 years, from 8 Mbps in2010 to 180 Mbps in 2021, and a similar growing trend isobservable worldwide [8]. Recent studies suggest that the added cost for faster Internet speeds — e.g., $50 monthly to boost from 200 to 300 Mbps with Comcast Xfinity — is not worth to most residential users, which consume only 5% of their available bandwidth. Several systemswere launched which allow users to monetize such spare bandwidth, e.g., distributed proxy or VPN (Virtual Private Network) services.

While such systems are attracting a considerable number of users, both as clients (buyers) and providers (sellers), little to nothing is known about such bandwidth marketplaces. We have identified distributed VPN (dVPNs) as the most concrete examples of such marketplaces because, in essence, a dVPN is a system which allows users to sell their spare bandwidth. The contribution of this work is an investigation of the dVPN ecosystem. We run active and passive measurements to characterize their footprint and performance.

The analysis of up to six months of dVPNs data shows that  the  three  major  dVPNs  (Mysterium, Sentinel, Tachyon ) compose together a fast-growing network footprint of thousands of nodes (sellers) located all over the world. These nodes offer download speeds comparable with ProtonVPN, a popular centralized VPN. Location-wise, the US is the most attractive market, with the majority of the traffic being destined to services located in the US.

<br>
<h3>Resources</h3>
<a href="https://ringdvpn.com/">RING: The first multi-vendors bandwidth marketplace</a>
<br>
<h3>Poster</h3>
Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2021). <a href="poster_ring.pdf">A First Look Into Distributed VPNs</a>. In IMC'21. <a href="poster_poster_ring.pdf">[Poster PDF]</a>
<br>
<h3>Publications</h3>
1. Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2022). <a href="../../publication/ring/">Monetizing Spare Bandwidth: the Case of Distributed VPNs</a>. To appear in SIGMETRICS'22.
