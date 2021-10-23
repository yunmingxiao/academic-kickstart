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

The average US household currently hosts more than 10 Inter-net of Things (IoT) devices. Many research papers have demonstrated critical security concerns of the IoT, often due to lack of best practices like partial usage of HTTP, or old ciphers. Even when best security practices are implemented, the IoT is still vulnerable to many attacks. Intruders can penetrate the home WiFi and directly control some IoT devices. They can compromise the account associated with an IoT device, mostly relying on username and password, or of third-party services like IFTTT. They can also compromise the devices where IoT apps run,i.e., mostly mobile phones.

The above security concerns could be mitigated via two-factor authentication(2FA), as commonly done for online banking. With 2FA, the user is often required to validate her identity via, for instance, an SMS received on a mobile phone. Unfortunately, requiring a user to constantly validate her interactions with IoT devices is cumbersome, and unlikely to be accepted by users – which is why it is not used.

The goal of this work is to build a frictionlessIoT authentication mechanism. Our rationale is that IoT traffic is highly predictable, due to being mostly caused by software, e.g., to report at constant rate temperature readings from a smart thermostat, and less frequently triggered by routines set by the user, e.g., “turn on the heat each night at 6pm”, or by user via manual input, e.g., increase the thermostat temperature from its companion app. Predictable traffic can be learned and automatically authorized. Unpredictable traffic, when legitimate, is associated with some physical interaction between the user and a controlling device. We thus plan to automatically validate unpredictable traffic leveraging sensor data from the device used to control an IoT device, e.g., accelerometer and gyroscope on a mobile phone.

Our first contribution is a quantification of the predictability of IoT traffic by analyzing public datasets. The analysis of public datasets shows that 80-90% of the IoT traffic (from hundred of devices) is indeed predictable. The second contribution of this work is the design of FIAT, a frictionless authentication mechanism for IoT traffic. FIAT is designed to improve the security of legacy IoT devices with minimal user input for authentication.

<!-- <br>
<h3>Resources</h3>
<a href="https://ringdvpn.com/">RING: The first multi-vendors bandwidth marketplace</a> -->
<br>
<h3>Poster</h3>
Yunming Xiao, Matteo Varvello (2021). <a href="TBD">Poster: FIAT: Frictionless Authentication of IoT Traffic</a>. In CoNEXT'21.
<br>
<h3>Publications</h3>
...
<!-- 1. Marc Anthony Warrior, Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2020). <a href="../../publication/dekodi/">De-Kodi: Understanding the Kodi Ecosystem</a>. In WWW’20. -->
