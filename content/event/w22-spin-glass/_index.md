---
title: Algorithmic Methods in Statistical Physics
cms_exclude: true

summary: ""

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""

weight: 20
---

{{< calendar "https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FChicago&title=Theoretical%20CS%20at%20UChicago&showPrint=0&showTitle=0&src=NjZwY2NvYnRwZ2QxaG8zbHY2ZmpoMmlmbWtAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&src=Y19vc2dmMWMxcWVtZHJhczhtdTdsN3BkaGpyc0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=YzU3c2hpY2k0NW0xN3FsMGdodmw1NmVrMzhAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&color=%23E67C73&color=%23AD1457&color=%23C0CA33" >}}

<!-- ***************** -->
<!-- EVENT DESCRIPTION -->
<!-- ***************** -->
---

This reading group will focus on understanding the technical details related to proving the Parisi variational principle, and its role in modern algorithmic applications of spin glass theory.

##### Topics Outline

- Introduction to the replica method, and its use in deriving Parisi's ansatz for the Sherrington-Kirkpatrick model.

- Demonstrate Panchenko's lowerbound argument for the Parisi variational principle. Focus specifically on the geometric intuition for the Gibbs distribution. Showcase fundamental tools for the argument:
    - Gaussian integration by parts, Gaussian concentration, and Stein's Lemma (the Gaussian toolbox)
    - Exchangeability via Gram-de Finetti arrays (Aldous-Hoover, Dovbysh-Sudakov)
    - Poisson processes and the Ruelle Probability Cascades
    - Pure state decompositions

- [Optional] Showcase the Guerra-Toninelli (smart-path) interpolation technique, and demonstrate their upperbound argument for the Parisi variational principle.

- Discuss the Gibbs distribution for spherical p-spin: pure states, thin bands, and their uses in constructing Subag's algorithm for finding the ground state.

- Present Montanari's algorithm for the Sherrington-Kirkpatrick model and where it takes inspiration from Subag's algorithm.

##### Reading List

- [_The Sherrington-Kirkpatrick Model_](https://drive.google.com/file/d/1WXbzgl61jtDz8V3r-m1lsE8-a8JEeA6p/view) (specifically chapters 1, 2, 3 and the bonus chapter)
    - *Dmitry Panchenko*

- [_Following the Ground State of full-RSB Spherical Spin Glass_](https://arxiv.org/abs/1812.04588)
    - *Eliran Subag*

- [_Optimization of the Sherrington-Kirkpatrick Hamiltonian_](https://arxiv.org/abs/1812.10897)
    - *Andrea Montanari*

##### Further Resources

See [here]({{< ref "event/w22-spin-glass/02-01-22/index.md" >}}) for a full reference list.

### Schedule

---
