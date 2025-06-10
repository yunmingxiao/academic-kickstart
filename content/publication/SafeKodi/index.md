---
title: "Decoding the Kodi Ecosystem"
authors:
- Yunming Xiao
- Matteo Varvello
- Marc Anthony Warrior
- Aleksandar Kuzmanovic
date: "2023-03-21T00:00:00Z"
doi: "10.1145/3563700"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-21T00:00:00Z"

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
publication: In *ACM Transactions on the Web* #In Proceedings of the *ACM on Measurement and Analysis of Computing Systems* 
publication_short: In *TWEB*

abstract: "Free and open source media centers are experiencing a boom in popularity for the convenience they offer users seeking to remotely consume digital content. Kodi is today’s most popular home media center, with millions of users worldwide. Kodi’s popularity derives from its ability to centralize the sheer amount of media content available on the Web, both free and copyrighted. Researchers have been hinting at potential security concerns around Kodi, due to add-ons injecting unwanted content as well as user settings linked with security holes. Motivated by these observations, this paper conducts the first comprehensive analysis of the Kodi ecosystem: 15,000 Kodi users from 104 countries, 11,000 unique add-ons, and data collected over 9 months.
<br><br>
Our work makes three important contributions. Our first contribution is that we build “crawling” software
(de-Kodi) which can automatically install a Kodi add-on, explore its menu, and locate (video) content. This
is challenging for two main reasons. First, Kodi largely relies on visual information and user input which
intrinsically complicates automation. Second, the potential sheer size of this ecosystem (i.e., number of available
add-ons) requires a highly scalable crawling solution. Our second contribution is that we develop a solution
to discover Kodi add-ons. Our solution combines Web crawling of popular websites where Kodi add-ons are
published (LazyKodi and GitHub) and SafeKodi, a Kodi add-on we have developed which leverages the help
of Kodi users to learn which add-ons are used in the wild and, in return, offers information about how safe
these add-ons are, e.g., do they track user activity or contact sketchy URLs/IP addresses. Our third contribution
is a classifier to passively detect Kodi traffic and add-on usage in the wild.
<br><br>
Our analysis of the Kodi ecosystem reveals the following findings. We find that most installed add-ons are
unofficial but safe to use. Still, 78% of the users have installed at least one unsafe add-on, and even worse, such
add-ons are among the most popular. In response to the information offered by SafeKodi, one-third of the
users reacted by disabling some of their add-ons. However, the majority of users ignored our warnings during
several months attracted by the content such unsafe add-ons have to offer. Last but not least, we show that
Kodi’s auto-update, a feature active for 97.6% of SafeKodi users, makes Kodi users easily identifiable by their
ISPs. While passively identifying which Kodi add-on is in use is, as expected, much harder, we also find that
many unofficial add-ons do not use HTTPS yet, making their passive detection straightforward."


tags:
#- 
featured: false

links:
# - name: ACM
#   url: https://doi.org/10.1145/3563700
url_pdf: publication/safekodi/decoding_kodi_tweb.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

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

<!-- <br> -->
<h3>Resources</h3>
<a href="https://safekodi.com/">SafeKodi: The first aggregator for (safe) Kodi addons</a>
<br>
<h3>Publications</h3>
1. Marc Anthony Warrior, Yunming Xiao, Matteo Varvello, Aleksandar Kuzmanovic (2020). <a href="../../publication/dekodi/">De-Kodi: Understanding the Kodi Ecosystem</a>. In WWW’20.
<br>
2. Yunming Xiao, Matteo Varvello, Marc Anthony Warrior, Aleksandar Kuzmanovic (2022). <a href="../../publication/safekodi/">Decoding the Kodi Ecosystem</a>. In TWEB.
<br>
<h3>Media Coverage</h3>
1. <a href="https://torrentfreak.com/safekodi-researchers-help-kodi-users-to-spot-malicious-addons-200306/">SafeKodi: Researchers Help Kodi Users to Spot Malicious Addons - TorretFreak.com</a><br>
2. <a href="https://www.technadu.com/safekodi-save-users-from-risky-kodi-addons/94748/">“SafeKodi” is Here to Save Users From Risky Kodi Addons - TechNadu.com</a><br>
3. <a href="https://www.express.co.uk/life-style/science-technology/1252981/Kodi-update-news-stream-warning-alert">Why streaming on this TV player just got a lot less dangerous - Daily Express</a><br>
4. <a href="https://www.adslzone.net/noticias/seguridad/safekodi-primer-antivirus-kodi/">Crean el primer antivirus para Kodi: protégete de addons con malware - AdslZone.net</a><br>
5. <a href="https://pplware.sapo.pt/software/safekodi-acabaram-se-os-addons-maliciosos-no-kodi/">SafeKodi: Acabaram-se os addons maliciosos no Kodi - Pplware.sapo.pt</a><br>
6. <a href="https://www.pcsteps.gr/331074-safekodi-%cf%80%cf%81%ce%bf%cf%83%cf%84%ce%b1%cf%83%ce%af%ce%b1-%ce%ba%ce%b1%ce%b9-%ce%b1%cf%83%cf%86%ce%b1%ce%bb%ce%ad%cf%82-streaming-%cf%83%cf%84%ce%bf-kodi/">SafeKodi: Προστασία Και Ασφαλές Streaming Στο Kodi v18.6 - PcSteps.gr</a><br>
7. <a href="https://www.vpncompare.co.uk/new-kodi-tool-safe/">The new Kodi tool that helps keep streamers safe - VPNCompre.co.uk</a><br>
8. <a href="https://yeeeah.fr/tech/safekodi-les-chercheurs-aident-les-utilisateurs-de-kodi-a-reperer-les-modules-malveillants">SafeKodi: les chercheurs aident les utilisateurs de Kodi à repérer les modules malveillants - Yeeeah.fr</a><br>
9. <a href="https://vpnbasen.se/forskargrupp-har-tagit-fram-safekodi-en-app-letar-efter-skadliga-tillagg/">Forskargrupp har tagit fram ”SafeKodi” – en app letar efter skadliga tillägg - VPNBasen.se</a><br>
10. <a href="https://www.fredzone.org/safekodi-pour-eviter-les-extensions-verolees-sur-kodi-288">SafeKodi, pour éviter les extensions vérolées sur Kodi - FredZone.org</a><br>
11. <a href="https://troypoint.com/safekodi/">Is Your Kodi Virus Free? Use SafeKodi to Scan & Fix - TroyPoint.com</a><br>
12. <a href="https://troypoint.com/safekodi/">SafeKodi: O maior aliado de quem usa o Kodi - NoticiasETecnologia.com</a><br>
......
<br>
<h3>Videos</h3>
Some nice videos to demonstrate the usage of SafeKodi: 

<a href="KODI 2020_NOVEDAD PARA KODI_EL ANTIVIRUS!! [720p].mp4">KODI 2020*NOVEDAD PARA KODI*EL ANTIVIRUS!!</a><br>
<a href="SafeKODI identifikuje nebezpečné doplnky.mp4">SafeKODI identifikuje nebezpečné doplnky</a><br>
<a href="https://www.youtube.com/watch?v=xCW_2v1vkWM">Is Your Kodi Virus Free? How to Scan With SafeKodi - TROYPOINT Vids</a><br>
<a href="https://www.youtube.com/watch?v=9outnVKMQ1E">SafeKodi</a><br>
<!-- <a href="https://www.youtube.com/watch?v=tLxmJLcaZq4">KODI 2020*NOVEDAD PARA KODI*EL ANTIVIRUS!! - tutvboxaldia kodi&Android</a><br> -->
...

<br>


<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/9outnVKMQ1E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
