---
title: "Using Optimization to Obtain a Width-Independent, Parallel, Simpler, and Faster Positive SDP Solver"
authors: 
- Zeyuan Allen-Zhu
- "Yin Tat Lee"
- "admin"
date: "2016-01-10"
#doi: "10.1137/1.9781611974331.ch127"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 27th ACM-SIAM Symposium on Discrete Algorithms"
publication_short: "SODA"

abstract: "We study the design of polylogarithmic depth algorithms for approximately solving packing and covering semidefinite programs (or positive SDPs for short). This is a natural SDP generalization of the well-studied positive LP problem.

Although positive LPs can be solved in polylogarithmic depth while using only $\\log^2 n/ \\epsilon^3$ parallelizable iterations [4], the best known positive SDP solvers due to Jain and Yao [18] require $\\log^14 n/ \\epsilon^13$ parallelizable iterations. Several alternative solvers have been proposed to reduce the exponents in the number of iterations [19, 30]. However, the correctness of the convergence analyses in these works has been called into question [30], as they both rely on algebraic monotonicity properties that do not generalize to matrix algebra.

In this paper, we propose a very simple algorithm based on the optimization framework proposed in [4] for LP solvers. Our algorithm only needs $\\log^2 n/ \\epsilon^3$ iterations, matching that of the best LP solver. To surmount the obstacles encountered by previous approaches, our analysis requires a new matrix inequality that extends Lieb-Thirring's inequality, and a sign-consistent, randomized variant of the gradient truncation technique proposed in [3, 4]."


# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "first-order methods"
- "positive SDPs"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/1507.02259
- name: SIAM
  url: https://epubs.siam.org/doi/10.1137/1.9781611974331.ch127

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
