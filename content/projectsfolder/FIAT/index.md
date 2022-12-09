---
title: "FIAT: Frictionless Authentication of IoT Traffic"
summary: We propose FIAT, a firctionless authentication mechanism for IoT traffic
tags:
#- Deep Learning
date: "2021-10-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: "https://safekodi.com"

image:
  caption: FIAT
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

Home IoT (Internet of Things) deployments are vulnerable to local adversaries, compromising a LAN, and remote adversaries, compromising either the accounts associated with IoT devices or third-party devices like mobile phones used to control the IoT. There is, however, a fundamental difference between an attacker and a legitimate IoT user: the physical interaction with the device (e.g., via a mobile app) used to operate the IoT. Such physical interactions can be used to build frictionless authentications. However, their integration with IoT requires each vendor to independently adopt them, which is both complex and expensive. We instead design and build FIAT, the first third-party mechanism to automatically authorize IoT traffic by learning recurring traffic and validating human actions behind unpredictable traffic. FIAT does not require modification of the IoT devices or apps, as it operates passively on network traffic. Our evaluation shows that FIAT achieves high accuracy with minimal impact on the user experience.

<!-- <br>
<h3>Resources</h3>
<a href="https://ringdvpn.com/">RING: The first multi-vendors bandwidth marketplace</a> -->
<br>
<h3>Poster</h3>
Yunming Xiao, Matteo Varvello (2021). <a href="poster_fiat.pdf">Poster: FIAT: Frictionless Authentication of IoT Traffic</a>. In CoNEXT'21.
<br>
<h3>Publication</h3>
Yunming Xiao, Matteo Varvello (2022). <a href="../../publication/fiat/">FIAT: Frictionless Authentication of IoT Traffic</a>. In CoNEXT'22.
<!-- <br>
<h3>Technical Report</h3>
Yunming Xiao, Matteo Varvello (2021). <a href="../../files/frictionless.pdf">FIAT: Frictionless Authentication of IoT Traffic</a>. 
<br> -->
<!-- <h3>Publications</h3>
... -->
<!-- 1. Marc Anthony Warrior, Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2020). <a href="../../publication/dekodi/">De-Kodi: Understanding the Kodi Ecosystem</a>. In WWW’20. -->
