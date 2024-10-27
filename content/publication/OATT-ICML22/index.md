---
title: "Practical Almost-Linear-Time Approximation Algorithms for Hybrid and Overlapping Graph Clustering" 
authors:
- Lorenzo Orecchia
- Konstantinos Ameranis
- Kunal Talwar
- Charalampos Tsourakakis
date: 2022-07-30
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

abstract: "Detecting communities in real-world networks and clustering similarity graphs are major data mining tasks with a wide range of applications in graph mining, collaborative filtering, and bioinformatics. In many such applications, overwhelming empirical evidence suggests that communities and clusters are naturally overlapping, i.e., the boundary of a cluster may contain both edges across clusters and nodes that are shared with other clusters, calling for novel hybrid graph partitioning algorithms (HGP). While almost-linear-time approximation algorithms are known for edge-boundary-based graph partitioning, little progress has been made on fast algorithms for HGP, even in the special case of vertex-boundary-based graph partitioning. In this work, we introduce a frame-work based on two novel clustering objectives, which naturally extend the well-studied notion of conductance to clusters with hybrid vertex-and edge-boundary structure. Our main algorithmic contributions are almost-linear-time algorithms O(log n)-approximation algorithms for both these objectives. To this end, we show that the cut-matching framework of (Khandekar et al., 2014) can be significantly extended to incorporate hybrid partitions. Crucially, we implement our approximation algorithm to produce both hybrid partitions and optimality certificates for large graphs, easily scaling to tens of millions of edges, and test our implementation on real-world datasets against other competitive baselines."

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
- name: ICML Slides
  url: https://icml.cc/media/icml-2022/Slides/16880_M2pKLQk.pdf
- name: PMLR
  url: https://proceedings.mlr.press/v162/orecchia22a.html


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
