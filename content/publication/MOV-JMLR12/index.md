---
title: "A Local Spectral Method for Graphs: With Applications to Improving Graph Partitions and Exploring Data Graphs Locally"
authors:
- Michael W. Mahoney
- Nisheeth K. Vishnoi
- Lorenzo Orecchia
date: "2012-01-01"
math: true


# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]


# Publication name and optional abbreviated publication name.
publication: "Journal of Machine Learning Research"
publication_short: JMLR

abstract: "The second eigenvalue of the Laplacian matrix and its associated eigenvector are fundamental features of an undirected graph, and as such they have found widespread use in scientific computing, machine learning, and data analysis. In many applications, however, graphs that arise have several \emph{local} regions of interest, and the second eigenvector will typically fail to provide information fine-tuned to each local region. In this paper, we introduce a locally-biased analogue of the second eigenvector, and we demonstrate its usefulness at highlighting local properties of data graphs in a semi-supervised manner. To do so, we first view the second eigenvector as the solution to a constrained optimization problem, and we incorporate the local information as an additional constraint; we then characterize the optimal solution to this new problem and show that it can be interpreted as a generalization of a Personalized PageRank vector; and finally, as a consequence, we show that the solution can be computed in nearly-linear time. In addition, we show that this locally-biased vector can be used to compute an approximation to the best partition _near_ an input seed set in a manner analogous to the way in which the second eigenvector of the Laplacian can be used to obtain an approximation to the best partition in the entire input graph. Such a primitive is useful for identifying and refining clusters locally, as it allows us to focus on a local region of interest in a semi-supervised manner. Finally, we provide a detailed empirical evaluation of our method by showing how it can applied to finding locally-biased sparse cuts around an input vertex seed set in social and information networks."

# Summary. An optional shortened abstract.
summary: 
tags:
- "regularization"
- "spectral methods"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: https://arxiv.org/abs/0912.0681
- name: JMLR
  url: http://jmlr.csail.mit.edu/papers/volume13/mahoney12a

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

