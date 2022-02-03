---
title: "Week 1 - Introduction and Overview"
event: Algorithmic Methods in Statistical Physics

math: true
subtitle: "[Antares Chen](https://antaresc.github.io/) University of Chicago"
summary: "[Antares Chen](https://antaresc.github.io/)"
abstract: "We introduce the Sherrington-Kirkpatrick model and Parisi's variational principle. We motivate key mathematical objects that emerge from proving the principle: (1) replica symmetry breaking, (2) Guerra-Toninelli interpolation, (3) ultrametricity, (4) pure state decompositions, (5) the Ruelle Probability Cascades, and (6) the cavity method. We conclude by outlining the high-level organization of subsequent presentations and a motivation for why study the Parisi variational principle from an algorithmic standpoint."

# Talk start and end times.
date: "2022-02-01T10:30:00Z"
date_end: "2022-02-01T12:00:00Z"
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

- We introduced the Sherrington-Kirkpatrick model, translating spin glass vocabulary such as overlap, the partition function, and free energy, to concepts in optimization.

- We stated the Parisi Variational Principle and attempted to build a geometric picture of how the dynamics in Parisi's equations evolve.

- We stated an anology between Parisi's equations and Hamilton-Jacobi equations where the "Hamiltonian" is given by the L2-norm squared.

- We outlined various conjectures regarding how certain first-order optimization methods such as (stochastic) gradient descent might arise from a more algorithmic proof of Parisi's Variational Principle, using how we currently understand them to arise from the studying Hamilton-Jacobi equations as an analogy.

- We stated the over-arching theme of this tutorial sequence, and outlined plans for subsequent meetings.

- **Next time** we focus on the mathematical objects that arise in proving Parisi's variational principle, and begin discussing the replica symmetry (breaking) ansatzen.


### Material

---

- [Presentation notes](https://uchicago.box.com/s/zp6vtd0embg2gzg4h7vka1c98cf464ag)

- [TBA] [Scribe notes]() by Juspreet Singh Sandhu


### Full Reference List

---

Historical origins of Parisi's variational principle

- (1975) [_Solvable model of a spin-glass_](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.35.1792) -- David Sherrington, Scott Kirkpatrick
- (1977) [_Solution of 'Solvable model of a spin glass'_](https://www.tandfonline.com/doi/abs/10.1080/14786437708235992) -- David J. Thouless, Philip W. Anderson, and Robert G. Palmer
- (1979) [_Toward a mean field theory for spin glasses_](https://www.sciencedirect.com/science/article/abs/pii/0375960179907084) -- Giorgio Parisi
- (1979) [_Infinite number of order parameters for spin-glasses_](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.43.1754) -- Giorgio Parisi
- (1980) [_A sequence of approximated solutions for the S-K model for spin glasses_](https://iopscience.iop.org/article/10.1088/0305-4470/13/4/009) -- Giorgio Parisi
- (1981) [_Random-energy model: an exactly solvable model of disordered systems_](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.24.2613) -- Bernard Derrida
- (1983) [_Order parameter for spin-glasses_](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.50.1946) -- Giorgio Parisi
- (1984) [_Replica symmetry breaking and the nature of the spin glass phase_](https://jphys.journaldephysique.org/articles/jphys/abs/1984/05/jphys_1984__45_5_843_0/jphys_1984__45_5_843_0.html) -- Marc Mezard, Giorgio Parisi, Nicolas Sourlas, Gerard Toulouse, Miguel Virasoro
- (1985) [_The microstructure of ultrametricity_](https://hal.archives-ouvertes.fr/jpa-00210073/document) -- Marc Mezard, Miguel Virasoro
- (1986) [_Metastable states in spin glasses_](https://www.worldscientific.com/doi/10.1142/9789812799371_0014) -- Alan J. Bray, Michael A. Moore
- (1986) Marc Mezard, Giorgio Parisi, and Miguel Virasoro's ["Spin Glass Theory and Beyond"](https://www.worldscientific.com/worldscibooks/10.1142/0271)

Proving the Parisi variational principle

- (1987) [_A mathematical reformulation of Derrida's REM and GREM_](https://link.springer.com/content/pdf/10.1007/BF01210613.pdf) -- David Ruelle
- (1998) [_The Sherrington-Kirkpatrick model: A challenge for mathematicians_](https://link.springer.com/article/10.1007%2Fs004400050147) -- Michele Talagrand
- (2002) [_The thermodynamic limit in mean field spin glass models_](https://arxiv.org/abs/cond-mat/0204280) -- Francesco Guerra, Fabio L. Toninelli
- (2003) [_An extended variational principle for the SK spin-glass model_](https://arxiv.org/abs/cond-mat/0306386) -- Michael Aizenman, Robert Sims, Shannon L. Starr
- (2006) [_The Parisi formula_](https://annals.math.princeton.edu/wp-content/uploads/annals-v163-n1-p04.pdf) -- Michele Talagrand
- (2006) _Parisi measures_ -- Michele Talagrand (a tutorial paper published to the Journal of Functional Analysis)
- (2011) [_The Parisi ultrametricity conjecture_](https://arxiv.org/abs/1112.1003) -- Dmitry Panchenko
- (2013) [_A Parisi formula for mixed p-spin models_](https://arxiv.org/abs/1112.4409) -- Dmitry Panchenko

Pure state geometry of the Gibbs distribution

- (2008) [_Clusters of solutions and replica symmetry breaking in random k-satisfiability_](http://chimera.roma1.infn.it/FEDERICO/Publications_files/2008_JSTAT_P04004.pdf) -- Andrea Montanari, Federico Ricci-Tersenghi, Guilhem Semerjian
- (2014) [_Approximate ultrametricity for random measures and applications to spin glasses_](https://arxiv.org/abs/1412.7076) -- Aukosh Jagganath
- (2015) [_The legendre structure of the Parisi formula_](https://arxiv.org/abs/1510.03414) -- Antonio Auffinger, Wei-Kuo Chen
- (2016) [_The Geometry of the Gibbs in Pure Spherical Spin Glass_](https://arxiv.org/abs/1604.00679) -- Eliran Subag
- (2018) [_Free Energy Landscape in Spherical Spin Glass_](https://arxiv.org/abs/1804.10576) -- Eliran Subag
- (2018) [_Geometric description of the spherical spin glass Gibbs measures and temperature chaos_](https://www.youtube.com/watch?v=20g2QjKI6M8) -- Gerard Ben Arous (CIRM talk)

Modern algorithmic applications of the variational principle

- (2010) [_The dynamics of message passing on dense graphs, with applications to compressed sensing_](https://arxiv.org/abs/1001.3448) -- Mohsen Bayati, Andrea Montanari
- (2018) [_Following the Ground State of full-RSB Spherical Spin Glass_](https://arxiv.org/abs/1812.04588) -- Eliran Subag
- (2018) [_Optimization of the Sherrington-Kirkpatrick Hamiltonian_](https://arxiv.org/abs/1812.10897) -- Andrea Montanari
- (2020) [_Optimization of mean-field spin glasses_](https://arxiv.org/abs/2001.00904) -- Ahmed Al Alaoui, Andrea Montanari, Mark Sellke
- (2020) [_Incremental Approximate Message Passing_](https://simons.berkeley.edu/talks/pedagogical-talk-analysis-approximate-message-passing-algorithms) -- Ahmed Al Alaoui (Simons semester on Computation Phase Transitions)
- (2021) [_Local algorithms for Maximum Cut and Minimum Bisection on locally treelike regular graphs of large degree_](https://arxiv.org/abs/2111.06813) -- Ahmed Al Alaoui, Andrea Montanari, Mark Sellke

Textbooks

- (2001) Hidetoshi Nishimori's ["Statistical Physics of Spin Glasses and Information Processing An Introduction"](http://inis.jinr.ru/sl/P_Physics/PT_Thermodynamics,%20statistical%20physics/PTin_Information%20theory/Nishimori%20Statistical.pdf)
- (2009) Marc Mezard, and Andrea Montanari's ["Information, Physics, and Computation"](https://web.stanford.edu/~montanar/RESEARCH/book.html)
- Dmitry Panchenko's ["The Sherrington-Kirkpatrick Model"](https://drive.google.com/file/d/1WXbzgl61jtDz8V3r-m1lsE8-a8JEeA6p/view) (specifically chapters 1, 2, 3 and the bonus chapter)
- Michele Talagrand's "Mean Field Models for Spin Glasses" [[Vol. 1]](https://link.springer.com/book/10.1007/978-3-642-15202-3) [[Vol. 2]](https://link.springer.com/book/10.1007/978-3-642-22253-5) (specifically chapters 1, 12, 13, 14)
- Michele Talagrand's [page on spin glass publications](http://michel.talagrand.net/spinglasses/)

Online lectures

- (2020) _A brief introduction to mean-field spin glass models_ [[1]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202006291000-Jagannath.html), [[2]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202006291130-Jagannath.html), [[3]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202006301002-Jagannath.html), [[4]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202006301131-Jagannath.html) -- Aukosh Jagganath (OOPS)
- (2020) [_Optimization of full-RSB spherical spin glasses_](https://www.youtube.com/watch?v=5o2EWCHRSCI) -- Eliran Subag (Simons semester on Computational Phase Transitions)
- (2021) [_TAP approach and optimization of full-RSB spherical spin glasses_](https://www.youtube.com/watch?v=0BawusRPxNs) -- Eliran Subag (OOPS)
- (2020) _Mean-field methods in high-dimensional statistics and nonconvex optimization_ [[1]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202007061001-Montanari.html), [[2]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202007071001-Montanari.html), [[3]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202007081001-Montanari.html), [[4]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202007091002-Montanari.html), [[5]](http://www.birs.ca/events/2020/summer-schools/20ss230/videos/watch/202007101000-Montanari.html) -- Andrea Montanari (OOPS)
- (2020) [_Incremental Approximate Message Passing_](https://simons.berkeley.edu/talks/pedagogical-talk-analysis-approximate-message-passing-algorithms) -- Ahmed Al Alaoui (Simons semester on Computation Phase Transitions)
- (2021) _Approximate Message Passing Algorithms_ [[1]](https://simons.berkeley.edu/talks/title-tba-17), [[2]](https://simons.berkeley.edu/talks/title-tba-18) -- Cynthia Rush (Simons semester on the Computational Complexity of Statistical Inference)
- (2021) _Optimal iterative algorithms for problems with random data_ [[1]](https://simons.berkeley.edu/talks/title-tba-15), [[2]](https://simons.berkeley.edu/talks/title-tba-16) -- Andrea Montanari (Simons semester on the Computational Complexity of Statistical Inference)

---
