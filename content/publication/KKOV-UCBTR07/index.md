---
title: "On a Cut-Matching Game for the Sparsest Cut Problem"
authors:
- Rohit Khandekar
- Subhash A. Khot
- Nisheeth K. Vishnoi
- Lorenzo Orecchia
date: "2007-01-01"
math: true


# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "UC Berkeley Technical Report"
publication_short: "UC Berkeley TR"

abstract: "We study the following game between a ``cut'' player C and a ``matching'' player M. The game starts with an empty graph G on a set V of n vertices." #In each round, the cut player chooses a bisection (S,V\S) of vertices and the matching player then adds a perfect matching M (not necessarily belonging to G) between S and V\S to the (multi-)graph G. The choices of the players in each round may depend on those in the previous rounds. The game ends when G becomes an edge-expander. The value of this game, denoted by Val(n,C,M), is the total number of rounds in the game before it ends. We study this game for its connection with the Sparsest Cut problem in undirected graphs: if there is a polynomial-time cut player C such that Val(n,C,M) < f(n) for all M, then there is a polynomial-time O(f(n))-approximation algorithm for the Sparsest Cut problem.We show that there is no cut player C, even unbounded-time, that can ensure Val(n,C,M) = o(GAP(n)<SUP>1/2</SUP>) for all matching players M, where GAP(n) is the integrality gap of the well-studied SDP with triangle inequality constraints for the Sparsest Cut problem. Recall that GAP(n) = Omega(log log n). Thus, we prove that this approach cannot yield a o(GAP(n)<SUP>1/2</SUP>)-approximation (and in particular, o((log log n)<SUP>1/2</SUP>)-approximation) algorithm for this problem. Furthermore, we show that there is a (super-polynomial time) cut player C* such that, for all M, we have Val(n,C*,M) = O(log n)."


# Summary. An optional shortened abstract.
summary: 
tags:
- "graph partitioning"
- "network flows"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: UCB TR
  url: http://www.eecs.berkeley.edu/Pubs/TechRpts/2007/EECS-2007-177.html

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
