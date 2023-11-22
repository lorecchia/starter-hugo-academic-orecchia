---
title: "Linear Coupling: An Ultimate Unification of Gradient and Mirror Descent" 
authors: 
- Zeyuan Allen-Zhu
- Lorenzo Orecchia
date: "2017-11-28"
#doi: "10.4230/LIPIcs.ITCS.2017.3"
math: true

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Innovations in Theoretical Computer Science Conference"
publication_short: "ITCS"

abstract: "First-order methods play a central role in large-scale machine learning. Even though many variations exist, each suited to a particular problem, almost all such methods fundamentally rely on two types of algorithmic steps: gradient descent, which yields primal progress, and mirror descent, which yields dual progress. We observe that the performances of gradient and mirror descent are complementary, so that faster algorithms can be designed by \"linearly coupling\" the two. We show how to reconstruct Nesterov's accelerated gradient methods using linear coupling, which gives a cleaner interpretation than Nesterov's original proofs. We also discuss the power of linear coupling by extending it to many other settings that Nesterov's methods cannot apply to."

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
  url: https://arxiv.org/abs/1407.1537
- name: ITCS
  url: https://drops.dagstuhl.de/opus/volltexte/2017/8185/

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
