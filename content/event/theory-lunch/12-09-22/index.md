---
title: "Polynomial-Time Algorithm for Power-Sum Decomposition of Polynomials"
event: Theory Lunch

math: true
subtitle: "[Jeff (Sichao) Xu](https://www.andrew.cmu.edu/user/sichaoxu/), Carnegie Mellon University"
summary: "[Jeff (Sichao) Xu](https://www.andrew.cmu.edu/user/sichaoxu/)"
abstract: "We give efficient algorithms for finding power-sum decomposition of an input polynomial $P(x)= \\sum_{i\\leq m} p_i(x)^d$ with component $p_i$s. The case of linear $p_i$s is equivalent to the well-studied tensor decomposition problem while the quadratic case occurs naturally in studying identifiability of non-spherical Gaussian mixtures from low-order moments.


Unlike tensor decomposition, both the unique identifiability and algorithms for this problem are not well-understood. For the simplest setting of quadratic $p_i$s and $d=3$, prior work of [GHK15] yields an algorithm only when $m \\leq \\widetilde{O}(\\sqrt{n})$. On the other hand, the more general recent result of [GKS20] builds an algebraic approach to handle any $m=n^{O(1)}$ components but only when $d$ is large enough (while yielding no bounds for $d=3$ or even $d=100$) and only handles an inverse exponential noise.


Our results obtain a substantial quantitative improvement on both the prior works above even in the base case of $d=3$ and quadratic $p_i$s. Specifically, our algorithm succeeds in decomposing a sum of $m \\sim \\widetilde{O}(n)$ generic quadratic $p_i$s for $d=3$ and more generally the $d$th power-sum of $m \\sim n^{2d/15}$ generic degree-$K$ polynomials for any $K \\geq 2$. Our algorithm relies only on basic numerical linear algebraic primitives, is exact (i.e., obtain arbitrarily tiny error up to numerical precision), and handles an inverse polynomial noise when the $p_i$s have random Gaussian coefficients.


Based on joint work with Mitali Bafna, Jun-Ting Hsieh and Pravesh Kothari.


FOCS '22. [Arxiv](https://arxiv.org/abs/2208.00122)."

# Talk start and end times.
date: "2022-12-09T12:00:00Z"
date_end: "2022-12-09T13:30:00Z"
location: "Cobb 301"
all_day: false
show_date: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors:
tags:
- theory lunch
- fall 2022

# Is this a featured talk? (true/false)
featured: false

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

math: True
share: False
show_related: False
profile: False
---

---

Join via [Zoom](https://uchicago.zoom.us/j/95507241990?pwd=NTZOemk4RmFoU1JvenpUTUZFcnlPUT09)
