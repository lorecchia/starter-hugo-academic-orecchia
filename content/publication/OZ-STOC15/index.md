---
title: "Nearly-Linear Time Packing and Covering LP Solver with Faster Convergence Rate"
authors:
- Zeyuan Allen-Zhu
- Lorenzo Orecchia
date: "2015-01-01"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 47th Annual ACM Symposium on Theory of Computing"
publication_short: "STOC"

abstract: "Packing and covering linear programs (PC-LPs) form an important class of linear programs (LPs) across computer science, operations research, and optimization. In 1993, Luby and Nisan constructed an iterative algorithm for approximately solving PC-LPs in nearly linear time, where the time complexity scales nearly linearly in N, the number of nonzero entries of the matrix, and polynomially in ε, the (multiplicative) approximation error. Unfortunately, all existing nearly linear-time algorithms for solving PC-LPs require time at least proportional to $ε−2$.
In this paper, we break this longstanding barrier by designing a packing solver that runs in time $Õ (Nε−1)$ and covering LP solver that runs in time $Õ (Nε−1.5)$. Our packing solver can be extended to run in time $Õ (Nε−1)$ for a class of well-behaved covering programs. In a follow-up work, Wang et al. showed that all covering LPs can be converted into well-behaved ones by a reduction that blows up the problem size only logarithmically.
At high level, these two algorithms can be described as linear couplings of several first-order descent steps. This is an application of our linear coupling technique to problems that are not amenable to blackbox applications known iterative algorithms in convex optimization."


# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "linear programming"
- "packing and covering linear programs"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ACM
  url: https://dl.acm.org/doi/10.1145/2746539.2746573
- name: ArXiv
  url: https://arxiv.org/abs/1411.1124

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
