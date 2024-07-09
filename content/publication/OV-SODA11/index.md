---
title: "Towards an SDP-Based Approach to Spectral Methods: A Nearly-Linear Time Algorithm for Graph Partitioning and Decomposition"
authors:
- Lorenzo Orecchia
- Nisheeth K. Vishnoi
date: "2011-01-01"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 22nd annual ACM-SIAM symposium on Discrete Algorithms
"
publication_short: "SODA"

abstract: "In this paper, we consider the following graph partitioning problem: The input is an undirected graph G = (V, E), a balance parameter b ∈ (0, 1/2] and a target conductance value γ ∈ (0, 1). The output is a cut which, if non-empty, is of conductance at most O(f), for some function f(G, γ), and which is either balanced or well correlated with all cuts of conductance at most γ. In a seminal paper, Spielman and Teng [16] gave an $Õ(|E|/γ2)$-time algorithm for $f = √γ log3 |V|$ and used it to decompose graphs into a collection of near-expanders [18].
We present a new spectral algorithm for this problem which runs in time $Õ(|E|/γ) for f = √γ$. Our result yields the first nearly-linear time algorithm for the classic Balanced Separator problem that achieves the asymptotically optimal approximation guarantee for spectral methods.
Our method has the advantage of being conceptually simple and relies on a primal-dual semidefinite-programming (SDP) approach. We first consider a natural SDP relaxation for the Balanced Separator problem. While it is easy to obtain from this SDP a certificate of the fact that the graph has no balanced cut of conductance less than γ, somewhat surprisingly, we can obtain a certificate for the stronger correlation condition. This is achieved via a novel separation oracle for our SDP and by appealing to Arora and Kale's [3] framework to bound the running time. Our result contains technical ingredients that may be of independent interest."


# Summary. An optional shortened abstract.
summary: 
tags:
- "graph partitioning"
- "spectral methods"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ACM
  url: https://dl.acm.org/doi/10.5555/2133036.2133078

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

