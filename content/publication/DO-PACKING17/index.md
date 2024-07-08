---
title: "Solving Packing and Covering LPs in $Õ(1ε2)$ Distributed Iterations with a Single Algorithm and Simpler Analysis"
authors:
- Jelena Diakonikolas
- Lorenzo Orecchia
date: "2017-10-24T00:00:00Z"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "ArXiv"
publication_short: "ArXiv"

abstract: "Packing and covering linear programs belong to the narrow class of linear programs that are efficiently solvable in parallel and distributed models of computation, yet are a powerful modeling tool for a wide range of fundamental problems in theoretical computer science, operations research, and many other areas. Following recent progress in obtaining faster distributed and parallel algorithms for packing and covering linear programs, we present a simple algorithm whose iteration count matches the best known $Õ (1ϵ2)$ for this class of problems. The algorithm is similar to the algorithm of [Allen-Zhu and Orecchia, 2015], it can be interpreted as Nesterov's dual averaging, and it constructs approximate solutions to both primal (packing) and dual (covering) problems. However, the analysis relies on the construction of an approximate optimality gap and a primal-dual view, leading to a more intuitive interpretation. Moreover, our analysis suggests that all existing algorithms for solving packing and covering linear programs in parallel/distributed models of computation are, in fact, unaccelerated, and raises the question of designing accelerated algorithms for this class of problems."


# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "first-order methods"
- "linear programming"
- "packing linear programs"
- "covering linear programs"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/1710.09002

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
