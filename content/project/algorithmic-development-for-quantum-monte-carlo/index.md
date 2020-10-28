---
title: Algorithmic Development for Quantum Monte Carlo
summary: Use parallelization, deep learning, and evolutionary computation for algorithmic improvements to continuous space quantum Monte Carlo methods.
tags:
- path integral quantum monte carlo
- PIMC
- continuous space quantum Monte Carlo
- quantum Monte Carlo
- QMC
- deep learning
- AI
- artificial intelligence
- deep learning
- machine learning
- evolutionary computation
date: "2020-10-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# Does this page contain LaTeX math? (true/false)
math: true

image:
  caption: ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Center"
  preview_only: false

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/nscottnichols
url_code: "https://github.com/DelMaestroGroup/PlatedHe4Nanopores"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""
---

One of the most important weapons in our arsenal for the attack on the quantum
many-body problem is the quantum Monte Carlo (QMC) algorithm. The ability to
[exactly simulate bosons in thermal equilibrium](https://doi.org/10.1103/RevModPhys.67.279) to within
statistical uncertainties has fostered a massive increase in our grasp of
quantum matter and exotic phases. A major aspect of my research has been through
core contributions to the [Del Maestro group continuous space QMC code](https://code.delmaestro.org/).
Society is currently coasting on the fumes of Moore's law which has made
abundantly clear that the most productive way to achieve more measurements,
larger system sizes, and better understanding of the quantum many-body problem
through the lens of QMC simulations is algorithmic improvements. One tantalizing
new prospect is applying machine learning to the spatial continuum. Open source
libraries offer the ability to use deep learning for phase discrimination and
perhaps learn more efficient traversal paths through the Markov chain. Possible
high impact outcomes include a sign-problem free QMC algorithm. Another course
for enhancement is to use evolutionary computation to optimize heuristically
chosen weights through optimization of number of measurements, autocorrelation
time, and CPU hours. I plan to continue development on QMC algorithms with a
focus on improving computational performance. Immediate gains can be realized
through leveraging parallel processing when calculating long range interactions
by adding CUDA support or porting the code to Julia. A code port could harness
built-in multithreading, LAPACK, and BLAS capabilities as well as have the
additional benefit of a lower barrier to entry for code development by the
scientific community.
