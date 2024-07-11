---
title: "A Simple, Combinatorial Algorithm for Solving SDD Systems in Nearly-Linear Time"
authors:
- Jonathan A. Kelner
- admin
- Aaron Sidford
- Zeyuan Allen-Zhu
date: "2013-01-28"
mate: true


publication: "Proceedings of the 45th annual ACM symposium on Theory of Computing"
publication_short: STOC

abstract: "In this paper, we present a simple combinatorial algorithm that solves symmetric diagonally dominant (SDD) linear systems in nearly-linear time. It uses little of the machinery that previously appeared to be necessary for a such an algorithm. It does not require recursive preconditioning, spectral sparsification, or even the Chebyshev Method or Conjugate Gradient. After constructing a "nice" spanning tree of a graph associated with the linear system, the entire algorithm consists of the repeated application of a simple update rule, which it implements using a lightweight data structure. The algorithm is numerically stable and can be implemented without the increased bit-precision required by previous solvers. As such, the algorithm has the fastest known running time under the standard unit-cost RAM model. We hope the simplicity of the algorithm and the insights yielded by its analysis will be useful in both theory and practice."

tags:
- "convex optimization"
- "Laplacian linear systems"
- "electrical flow"

links:
- name: ArXiv 
  url: http://arxiv.org/abs/1301.6628
- name: ACM
  url: http://dl.acm.org/citation.cfm?id=2488724
---
