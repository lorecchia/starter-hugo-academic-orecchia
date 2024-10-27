---
title: "Fast Algorithms for Hypergraph PageRank with Applications to Semi-Supervised Learning" 
authors: 
- Konstantinos Ameranis
- Antares Chen
- Lorenzo Orecchia
- Erasmo Tani
date: "2023-7-30"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning"
publication_short: "ICML"

abstract: "Despite there being significant work on developing spectral, and metric embedding based approximation algorithms for hypergraph generalizations of conductance, little is known regarding the approximability of hypergraph partitioning objectives beyond this.
This work proposes algorithms for a general model of hypergraph partitioning that unifies both undirected and directed versions of many well-studied partitioning objectives. The first contribution of this paper introduces polymatroidal cut functions, a large class of cut functions amenable to approximation algorithms via metric embeddings and routing multicommodity flows. We demonstrate an O($$\\sqrt{\\log n}$$)-approximation, where n is the number of vertices in the hypergraph, for these problems by rounding relaxations to metrics of negative-type.
The second contribution of this paper generalizes the cut-matching game framework of Khandekar et. al. to tackle polymatroidal cut functions. This yields the first almost-linear time $$O(\\log n)$$-approximation algorithm for standard versions of undirected and directed hypergraph partitioning. A technical consequence of our construction is that a cut-matching game which greatly relaxes the set of allowed actions for both players can be used to partition hypergraphs with negligible impact on the approximation ratio. We believe this to be of independent interest."

# Summary. An optional shortened abstract.
summary: 
tags:
- "hypergraphs"
- "cut-matching game"
- "graph partitioning"
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/2301.08920


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
