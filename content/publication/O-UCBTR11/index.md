---
title: "Fast Approximation Algorithms for Graph Partitioning Using Spectral and Semidefinite-Programming Techniques"
authors:
- admin
date: 2011-05-01
math: True

# Schedule page publish date (NOT publication's date).
#publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "UC Berkeley Dissertation"
publication_short: "UC Berkeley Dissertation"

abstract: "Graph partitioning problems are a central topic of research in the study of approximation algorithms. They are of interest to theoretical computer scientists for their far-reaching connections to spectral graph theory, metric embeddings and inapproximability theory. And they are also important for many practitioners, as algorithms for graph partitioning are often fundamental primitives in the solution of other problems, such as image segmentation, clustering and social-network analysis.

While many theoretical approximation algorithms exist for graph partitioning, they often rely on multicommodity-flow computations that are quadratic time in the worst case and are too time-consuming for the massive graphs that are prevalent in today's applications. In this thesis, we study the design of approximation algorithms that yield strong approximation ratios, while running in subquadratic time and relying on computational procedures that are often fast in practice.

Our algorithms employ spectral and s-t flow operations to explore the cuts of a graph in a very efficient way. A crucial ingredient in their design is the usage of random walks that capture the sparse cuts of a graph better than single eigenvectors. The analysis of our methods is particularly simple, as it relies on a semidefinite programming formulation of the graph partitioning problem of choice. Indeed, we can develop our algorithms as primal-dual methods for solving a semidefinite program and show that certain random walks arise naturally from this approach."

tags:
- "graph partitioning"
- "network flows"
- "spectral methods"

links:
- name: UCB TR
  url: http://www.eecs.berkeley.edu/Pubs/TechRpts/2011/EECS-2011-56.html

---
