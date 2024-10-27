---
title: "Hypergraph Diffusions and Resolvents for Norm-Based Hypergraph Laplacians" 
authors: 
- Konstantinos Ameranis
- Antares Chen
- Adela Frances DePavia
- Lorenzo Orecchia
- Erasmo Tani
date: 2023-07-01
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: "International Conference on Machine Learning"
#publication_short: "ICML"

abstract: "The development of simple and fast hypergraph spectral methods has been hindered by the lack of numerical algorithms for simulating heat diffusions and computing fundamental objects, such as Personalized PageRank vectors, over hypergraphs. In this paper, we overcome this challenge by designing two novel algorithmic primitives. The first is a simple, easy-to-compute discrete-time heat diffusion that enjoys the same favorable properties as the discrete-time heat diffusion over graphs. This diffusion can be directly applied to speed up existing hypergraph partitioning algorithms. Our second contribution is the novel application of mirror descent to compute resolvents of non-differentiable squared norms, which we believe to be of independent interest beyond hypergraph problems. Based on this new primitive, we derive the first nearly-linear-time algorithm that simulates the discrete-time heat diffusion to approximately compute resolvents of the hypergraph Laplacian operator, which include Personalized PageRank vectors and solutions to the hypergraph analogue of Laplacian systems. Our algorithm runs in time that is linear in the size of the hypergraph and inversely proportional to the hypergraph spectral gap $$\\lambda_G$$, matching the complexity of analogous diffusion-based algorithms for the graph version of the problem."

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
- name: ArXiv
  url: https://arxiv.org/abs/2307.11042



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
