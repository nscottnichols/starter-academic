---
title: Analytic Continuation Problem
summary: Direct comparison of experimental spectra with imaginary time density-density correlation functions
tags:
- continuous space quantum Monte Carlo
- quantum Monte Carlo
- QMC
- analytic continuation
- deep learning
- AI
- artificial intelligence
- deep learning
- machine learning
- evolutionary computation
- differential evolution
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
url_code: "https://github.com/nscottnichols/DEAC.jl"
url_pdf: ""
url_slides: "https://absuploads.aps.org/presentation.cfm?pid=16283"
url_video: "https://youtu.be/4bx6fcHMfMU"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""
---

For over thirty years a long standing problem in quantum many-body physics has
been to reliably extract dynamical information from imaginary time quantum Monte
Carlo data. Sch\"uttler and Scalapino were the first to highlight the intrinsic
difficulty by using a [least-squares approach](https://doi.org/10.1103/PhysRevLett.55.1204). The solution
which amounts to performing an inverse Laplace transform to recover spectral
functions became known as a notoriously ill-posed problem. Modern techniques use
Bayesian inference with regularization ([maximum entropy method](https://doi.org/10.1016/0370-1573(95)00074-7)),
[stochastic optimization](https://doi.org/10.1103/PhysRevB.94.125149), and [genetic algorithms](https://doi.org/10.1080/23746149.2017.1288585)
to approximate suitable results. These approaches often fail for experimentally
relevant data collected at finite temperatures or data containing large relative
uncertainties due to statistically low sampling rates at larger imaginary time
steps. Additionally, these methods are prone to large parameter sweeps and
critical slowing down causing increased user input and computational effort. A
new method using current evolutionary computation routines is developed to
assuage these stumbling blocks. The [Differential Evolution for Analytic
Continuation (DEAC) algorithm](https://absuploads.aps.org/presentation.cfm?pid=16283) is a parameter free method
that uses self adaptive differential evolution to extend the domain of imaginary
time density-density correlation functions and reconstruct accurate
representations of dynamic structure factor spectra at zero and finite
temperatures. Preliminary outcomes indicate huge speedup and resolving power
over other traditional and state-of-the-art methods. I will continue algorithmic
development of these techniques through hyphenated methods combining DEAC with
other analytic continuation techniques to offer improved quality of spectra.
Another exciting avenue for development is using a machine-learning approach
extending [previous work](https://doi.org/10.1103/PhysRevB.98.245101) to finite temperatures.
