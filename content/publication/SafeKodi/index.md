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
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3563700
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
