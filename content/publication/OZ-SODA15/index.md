---
title: "Using Optimization to Break the Epsilon Barrier: A Faster and Simpler Width-Independent Algorithm for Solving Positive Linear Programs in Parallel"
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
publication: Proceedings of the 26th Annual ACM-SIAM Symposium on Discrete Algorithms
publication_short: SODA

abstract: "We study the design of nearly-linear-time algorithms for approximately solving positive linear programs. Both the parallel and the sequential deterministic versions of these algorithms require $Õ(∈−4)$ iterations, a dependence that has not been improved since the introduction of these methods in 1993 by Luby and Nisan. Moreover, previous algorithms and their analyses rely on update steps and convergence arguments that are combinatorial in nature, and do not seem to arise naturally from an optimization viewpoint. In this paper, we leverage insights from optimization theory to construct a novel algorithm that breaks the longstanding $Õ(∈−4) barrier$. Our algorithm has a simple analysis and a clear motivation. Our work introduces a number of novel techniques, such as the combined application of gradient descent and mirror descent, and a truncated, smoothed version of the standard multiplicative weight update, which may be of independent interest."


# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "linear programming"
- "packing linear programs"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: http://arxiv.org/abs/1407.1925
- name: ACM
  url: http://dl.acm.org/citation.cfm?id=2722129.2722224

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

