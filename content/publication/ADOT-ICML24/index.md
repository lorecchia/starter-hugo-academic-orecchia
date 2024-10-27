---
title: "Fast Algorithms for Hypergraph PageRank with Applications to Semi-Supervised Learning" 
authors: 
- Konstantinos Ameranis
- Adela Frances DePavia
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

abstract: "A fundamental approach to semi-supervised learning is to leverage the structure of the sample space to diffuse label information from annotated examples to unlabeled points. Traditional methods model the input data points as a graph and rely on fast algorithms for solving Laplacian systems of equations, such as those defining PageRank. However, previous work has demonstrated that graph-based models fail to capture higher-order relations, such as group membership, which are better modeled by hypergraphs. Unfortunately, the scalable application of hypergraph models has been hampered by the non-linearity of the hypergraph Laplacian. In this paper, we present highly scalable algorithms for hypergraph primitives, such as hypergraph PageRank vectors and hypergraph Laplacian systems, over general families of hypergraphs. In addition to giving strong theoretical guarantees, we empirically showcase the speed of our algorithms on benchmark instances of semi-supervised learning on categorical data. We exploit their generality to improve semi-supervised manifold clustering via hypergraph models. By providing significant speed-ups on fundamental hypergraph tasks, our algorithms enable the deployment of hypergraph models on a massive scale."

# Summary. An optional shortened abstract.
summary: 
tags:
- "hypergraphs"
- "first-order methods"
- "spectral algorithms"
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ICML Poster
  url: https://icml.cc/virtual/2024/poster/32899
- name: PMLR
  url: https://proceedings.mlr.press/v235/ameranis24a.html


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
