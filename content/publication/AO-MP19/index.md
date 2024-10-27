---
title: "Nearly Linear-Time Packing and Covering LP Solvers" 
authors: 
- Zeyuan Allen-Zhu
- Lorenzo Orecchia
date: 2019-05-01
#doi: "10.1007/s10107-018-1244-x"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematical Programming: Series A and B"
publication_short: "Math. Program."

abstract: "Packing and covering linear programs (PC-LP s) form an important class of linear programs (LPs) across computer science, operations research, and optimization. Luby and Nisan (STOC 1993) constructed an iterative algorithm for approximately solving PC-LP s in nearly linear time, where the time complexity scales nearly linearly in $N$, the number of nonzero entries of the matrix, and polynomially in $\\varepsilon $, the (multiplicative) approximation error. Unfortunately, existing nearly linear-time algorithms for solving PC-LP s require time at least proportional to $\\varepsilon ^{-2}$. In this paper, we break this longstanding barrier by designing a packing solver that runs in time $\\widetilde{O}(N \\varepsilon ^{-1})$ and covering LP solver that runs in time $\\widetilde{O}(N \\varepsilon ^{-1.5})$. Our packing solver can be extended to run in time $\\widetilde{O}(N \\varepsilon ^{-1})$O for a class of well-behaved covering programs. In a follow-up work, Wang et al. (ICALP 2016) showed that all covering LPs can be converted into well-behaved ones by a reduction that blows up the problem size only logarithmically."

# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "first-order methods"
- "positive programs"
- "allocation"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ACM
  url: https://dl.acm.org/doi/10.1007/s10107-018-1244-x

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
