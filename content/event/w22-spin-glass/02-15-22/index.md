---
title: "Week 3 - The Replica Symmetric Estimate of SK Free Energy"
event: Algorithmic Methods in Statistical Physics

math: true
subtitle: "[Antares Chen](https://antaresc.github.io/) University of Chicago"
summary: "[Antares Chen](https://antaresc.github.io/)"
abstract: "We begin by introducing the limit identity that drives the replica method calcuation, and give an overview of how the computations are carried out. We then compute the action integral form of the free energy, and give an overview of the family of Replica Symmetry Breaking ansatzen. We conclude by computing the replica symmetric free energy estimate."

# Talk start and end times.
date: "2022-02-15T10:30:00Z"
date_end: "2022-02-15T12:00:00Z"
location: "JCL 390"
all_day: false
show_date: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors:
tags:
- statistical physics
- winter 2022

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

share: False
show_related: False
profile: False
---

### Recap of the Meeting

---

We began our discussion of the replica method by discussing the replica limit identity

- The following identity holds when the expectation is taken over a distribution with finite moments.
$$
\mathbb{E} \big[ \log Z_n(\beta) \big]
= \lim_{r \rightarrow 0} \frac{1}{r} \cdot \log \Big( \mathbb{E} \big[ Z_n^r \big] \Big)
$$

- The replica method is then a heuristic computation method used to estimate the free energy via the above limit identity like so
$$
\lim_{n \rightarrow \infty} \frac{1}{n} \mathbb{E} \big[ \log Z_n(\beta) \big]
\approx \lim_{n \rightarrow \infty} \lim_{r \rightarrow 0} \frac{1}{nr} \cdot \log \Big( \mathbb{E} \big[ Z_n^r \big] \Big)
$$

We then spent the meeting on discussing

- An overview to different stages of the replica computation: Pre-ansatzen, ansatzen, and post-ansatzen

- Reasons why the replica method is a heuristic method of computation

- The replica symmetric ansatzen, and a sketch of $k$-replica symmetry breaking

- The initial steps of the computation required to deduce the action (exponential) integral form of the free energy.

We ended on an expression for $\mathbb{E} \big[ Z_n^r \big]$ given by

$$
\mathbb{E} \big[ Z_n^r \big]
= \sum_{\\\{ \sigma^{(a)}_i \\\}_a} \prod_{i,j}^n \sqrt{\frac{n}{2\pi}} \int e^{- \frac{n}{2} \cdot z_{ij}^2} \cdot \exp \bigg( \beta \sum_{a=1}^r z_{ij} \cdot \sigma_i^{(a)} \sigma_j^{(a)} \bigg) \\\, dz_{ij}
$$




### Material

---

- [[pdf]](https://uchicago.box.com/s/4wwhcq2qacumyt1nirratd85iqtaataj) Scanned presentation notes

---
