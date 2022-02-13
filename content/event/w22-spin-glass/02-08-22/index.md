---
title: "Week 2 - Revisiting Parisi's Equations and the Replica Method"
event: Algorithmic Methods in Statistical Physics

math: true
subtitle: "[Antares Chen](https://antaresc.github.io/) University of Chicago"
summary: "[Antares Chen](https://antaresc.github.io/)"
abstract: "We revisit our geometric interpretation of the Parisi equations via a few interactive demos. We then discuss the historical origins of the Parisi Variational Principle via the Replica method. We demonstrate calculations leading to the action integral form of the replicated free energy, setting us up to introduce Replica Symmetry Breaking next time."

# Talk start and end times.
date: "2022-02-08T10:30:00Z"
date_end: "2022-02-08T12:00:00Z"
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

We spent most of our time discussing geometric intuition for the dynamics described by the Parisi's PDEs.

- The equations are given as
$$
\begin{cases}
    \Phi_t(t, x) = - \frac{\beta^2}{2} \cdot \big( \Phi_{xx}(t, x) + \mu(t) \cdot \lvert \Phi_x(t, x) \rvert^2 \big) \\\\
    \Phi(1, x) = \log \big( 2 \cdot \cosh x \big)
\end{cases}
$$

- When a change of variable is performed $t(s) = 1 - s$, the PDE becomes
$$
\begin{cases}
    \Phi_s(s, x) = \frac{\beta^2}{2} \cdot \big( \Phi_{xx}(s, x) + \mu( 1 - s ) \cdot \lvert \Phi_x(s, x) \rvert^2 \big) \\\\
    \Phi(0, x) = \log \big( 2 \cdot \cosh x \big)
\end{cases}
$$

- The behavior of this dynamic can be interpreted as follows. At time $s = 0$, we begin with the soft absolute value function $\Phi(0, x) = \log \big( 2 \cdot \cosh x \big)$. As $s$ progresses from $0 \rightarrow 1$, the evolution of $\Phi(s, x)$ is always affected by heat diffusion dynamics
$$- \frac{\beta^2}{2} \cdot \Phi_{xx}(t, x)$$

- On the other hand, $\mu(1 - s)$ is non-increasing on the interval $[0, 1]$. The function $\mu(s)$ itself is the cumulative density function of some measure supported on $[0, 1]$. Thus, the evolution of $\Phi(s, x)$ is also affected by a "gradient descent" dynamic $$\frac{\beta^2}{2} \cdot \lvert \Phi_x(s, x) \rvert^2$$
whose weight is dampened as $s$ increases towards $s = 1$.

This picture was helpful to have. It plots the evolution of $\Phi(s, x)$ from $s = 0 \rightarrow 1$

{{< figure src="/media/img/w22-spin-glass/02-08-22-image00.jpeg" >}}

where, on the right, the red contour corresponds to $s = 0$, the navy contour corresponds to $s = 1$, and $\mu(t)$ is given by the CDF of a Gaussian centered at $\frac{1}{2}$ with variance $\frac{1}{100}$

{{< figure src="/media/img/w22-spin-glass/02-08-22-image01.png" width=400px >}}

When thinking of $\mu(1 - s)$, consider the above picture as "backwards" i.e. think of $t$ progressing from $1 \rightarrow 0$.

### Material

---

- [[pdf]](https://uchicago.box.com/s/jr3wpjbez9txgcpcp0l1qykm4pjcv733) Scanned presentation notes

- [[demo]](https://www.wolframcloud.com/obj/7c33d701-c08b-4de2-bbba-6fc7888336ee) [[source]](https://uchicago.box.com/s/4hd1v9wulou9e4bwmjnvtnwuw4e999ra) Plotting Parisi's equations

- [[link]](https://hackmd.io/7uHy7d7CR_O_5mZtZOcWQA?both) Scribe notes -- Juspreet Singh Sandhu (see *Day 2*)

---
