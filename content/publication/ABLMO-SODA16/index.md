---
title: "Expanders via Local Edge Flips" 
authors: 
- Zeyuan Allen-Zhu
- Aditya Bhaskara
- Silvio Lattanzi
- Vahab Mirrokni
- admin
date: "2016-01-10"
#doi: "10.5555/2884435.2884454"
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

abstract: "Designing distributed and scalable algorithms to improve network connectivity is a central topic in peer-to-peer networks. In this paper we focus on the following well-known problem: given an n-node d-regular network for d = Ω(log n), we want to design a decentralized, local algorithm that transforms the graph into one that has good connectivity properties (low diameter, expansion, etc.) without affecting the sparsity of the graph. To this end, Mahlmann and Schindelhauer introduced the random \"flip\" transformation, where in each time step, a random pair of vertices that have an edge decide to 'swap a neighbor'. They conjectured that performing O(nd) such flips at random would convert any connected d-regular graph into a d-regular expander graph, with high probability. However, the best known upper bound for the number of steps is roughly O(n17d23), obtained via a delicate Markov chain comparison argument.\\

Our main result is to prove that a natural instantiation of the random flip produces an expander in at most O(n2d2[EQUATION] n) steps, with high probability. Our argument uses a potential-function analysis based on the matrix exponential, together with the recent beautiful results on the higher-order Cheeger inequality of graphs. We also show that our technique can be used to analyze another well-studied random process known as the 'random switch', and show that it produces an expander in O(nd) steps with high probability."

# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "first-order methods"
- "acceleration"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/1510.07768
- name: ACM
  url: https://dl.acm.org/doi/10.5555/2884435.2884454

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
