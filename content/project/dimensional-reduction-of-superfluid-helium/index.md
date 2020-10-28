---
title: Dimensional Reduction of Superfluid Helium
summary: Realize a Tomanaga-Luttinger liquid of helium.
tags:
- quantum Monte Carlo
- QMC
- Tomonaga-Luttinger liquid
- TLL
- nanopores
- low dimensional critical phenomena
- low temperature
- adsorption
- helium
date: "2020-10-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# Does this page contain LaTeX math? (true/false)
math: true

image:
  caption: '**Dimensional Reduction of Superfluid Helium** A quasi-one-dimensional chain of helium atoms may be achieved through preplating nanoporous materials with rare gases.'

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Bottom"
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

One dimensional quantum many body systems have been of long standing interest
due to profound differences from their two- and three-dimensional counterparts.
[Tomonaga-Luttinger liquid (TLL) theory](https://doi.org/10.1103/PhysRevLett.47.1840)
is expected to describe these systems at low energies but exhaustive testing has
not been possible due to the difficulties in realizing good model systems with a
tunable Luttinger interaction parameter. Helium in quasi-one-dimensional
confinement presents an excellent platform to study the emergence of a TLL over
a broad range of interaction strengths. In collaboration with an experimental
group (P. Sokol (IU)) at the forefront of this field, a [well-characterized
platform for one-dimensional confinement of helium has been developed](https://doi.org/10.1103/PhysRevB.102.144505).
The molecular sieve Mobil composition of matter No. 41 (MCM-41) preplated with a
monolayer of argon gas offers enough constriction to prevent the formation of
bulk fluid (with pores hundreds of nanometers long). Instead, concentric shells
of helium form along the pore walls until a single channel of helium forms at
the center. The formation of this structure is no coincidence as the MCM-41 pore
diameter and preplating rare gas have been carefully chosen such that the ratio
of the effective pore radius to the distance between shells (set by the helium
interaction potential) is approaching an integer. Large scale quantum Monte
Carlo simulations of the helium/MCM-41 system show tunability in the density of
the central helium column. I will continue my work through further
characterization the confinement environment by marrying grand canonical Monte
Carlo molecular simulation software with classical molecular dynamics
for a closer description of the interaction potential as well as through the
development of new technologies (See [Analytic Continuation Problem](https://nathan.nichols.live)) to compare imaginary-time quantum Monte
Carlo data with experimental measurements. Additional study is required to
confirm TLL-like behavior.
