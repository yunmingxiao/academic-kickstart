---
title: "Direct Nonlinear Acceleration"
authors:
- Aritra Dutta
- El Houcine Bourger
- Yunming Xiao
- Marco Canini
- Peter Richtarik
date: "2022-10-12T00:00:00Z"
doi: "10.1016/j.ejco.2022.100047"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication topic.
# Legend: 0 = Security and Privacy; 1 = System Reliability; 2 = MLSys; 
# 3 = Federated Learning; 4 = Blockchain; 5 = Undergraduate Projects;  6 = Uncategorized; 
publication_topics: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *EURO Journal on Computational Optimization*
publication_short: In *EURO Journal on Computational Optimization*

abstract: Optimization acceleration techniques such as momentum play a key role in state-of-the-art machine learning algorithms. Recently, generic vector sequence extrapolation techniques, such as regularized nonlinear acceleration (RNA) of Scieur et al., were proposed and shown to accelerate fixed point iterations. In contrast to RNA which computes extrapolation coefficients by (approximately) setting the gradient of the objective function to zero at the extrapolated point, we propose a more direct approach, which we call direct nonlinear acceleration (DNA). In DNA, we aim to minimize (an approximation of) the function value at the extrapolated point instead. We adopt a regularized approach with regularizers designed to prevent the model from entering a region in which the functional approximation is less precise. While the computational cost of DNA is comparable to that of RNA, our direct approach significantly outperforms RNA on both synthetic and real-world datasets. While the focus of this paper is on convex problems, we obtain very encouraging results in accelerating the training of neural networks.

tags:
- Machine Learning
featured: false

links:
- name: ArXiv
  url: https://arxiv.org/abs/1905.11692
url_pdf: publication/dna/dna-dutta-euro.pdf
# url_pdf: https://www.sciencedirect.com/sdfe/reader/pii/S2192440622000235/pdf
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

