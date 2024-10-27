---
title: "An Almost-Linear-Time Algorithm for Approximate Max Flow in Undirected Graphs, and its Multicommodity Generalizations"
authors: 
- Jonathan A. Kelner
- YinTat Lee
- Lorenzo Orecchia
- Aaron Sidford
date: 2014-01-01
doi: "10.1137/1.9781611973402.16"
math: true

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]
publication: Proceedings of the 25th Annual ACM-SIAM Symposium on Discrete Algorithms
publication_short: SODA

abstract: "In this paper, we introduce a new framework for approximately solving flow problems in capacitated, undirected graphs and apply it to provide asymptotically faster algorithms for the maximum s-t flow and maximum concurrent multicommodity flow problems. For graphs with n vertices and m edges, it allows us to find an ϵ-approximate maximum s-t flow in time $O(m1+o(1)ϵ−2)$, improving on the previous best bound of $Õ (mn1/3poly(1/ϵ)).$ Applying the same framework in the multicommodity setting solves a maximum concurrent multicommodity flow problem with k commodities in $O(m1+o(1)ϵ−2k2$ time, improving on the existing bound of $Õ(m4/3poly(k,ϵ−1)$.
Our algorithms utilize several new technical tools that we believe may be of independent interest:
- We give a non-Euclidean generalization of gradient descent and provide bounds on its performance. Using this, we show how to reduce approximate maximum flow and maximum concurrent flow to the efficient construction of oblivious routings with a low competitive ratio.
- We define and provide an efficient construction of a new type of flow sparsifier. In addition to providing the standard properties of a cut sparsifier our construction allows for flows in the sparse graph to be routed (very efficiently) in the original graph with low congestion.
- We give the first almost-linear-time construction of an O(mo(1))-competitive oblivious routing scheme. No previous such algorithm ran in time better than Ω̃ (mn).
We also note that independently Jonah Sherman produced an almost linear time algorithm for maximum flow and we thank him for coordinating submissions."

# Summary. An optional shortened abstract.
summary: 
tags:
- "convex optimization"
- "combinatorial preconditioning"
- "network flows"
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: ArXiv
  url: http://arxiv.org/abs/1304.2338
- name: SIAM
  url: http://epubs.siam.org/doi/pdf/10.1137/1.9781611973402.16
---

 *Co-winner of Best Paper Award at SODA 2014.*
