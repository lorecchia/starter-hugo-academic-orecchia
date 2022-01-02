---
title: "Accelerated Extra-Gradient Descent: A Novel Accelerated First-Order Method" 
authors: 
- Jelena Diakonikolas
- admin
date: "2018-12-01"
#doi: "10.1137/19M1288516"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Innovations in Theoretical Computer Science Conference"
publication_short: "ITCS"

abstract: "We provide a novel accelerated first-order method that achieves the asymptotically optimal convergence rate for smooth functions in the first-order oracle model. To this day, Nesterov's Accelerated Gradient Descent (AGD) and variations thereof were the only methods achieving acceleration in this standard blackbox model. In contrast, our algorithm is significantly different from AGD, as it relies on a predictor-corrector approach similar to that used by Mirror-Prox [Nemirovski, 2004] and Extra-Gradient Descent [Korpelevich, 1977] in the solution of convex-concave saddle point problems. For this reason, we dub our algorithm Accelerated Extra-Gradient Descent (AXGD). Its construction is motivated by the discretization of an accelerated continuous-time dynamics [Krichene et al., 2015] using the classical method of implicit Euler discretization. Our analysis explicitly shows the effects of discretization through a conceptually novel primal-dual viewpoint. Moreover, we show that the method is quite general: it attains optimal convergence rates for other classes of objectives (e.g., those with generalized smoothness properties or that are non-smooth and Lipschitz-continuous) using the appropriate choices of step lengths. Finally, we present experiments showing that our algorithm matches the performance of Nesterov's method, while appearing more robust to noise in some cases."

# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "first-order methods"
- "acceleration"
- "block-coordinate descent"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/1706.04680
- name: ITCS
  url: https://drops.dagstuhl.de/opus/volltexte/2018/8356/

url_preprint: 
url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
#image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
