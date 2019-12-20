---
title: "Evaluation of linear autoregressive models for estimation of energy spectra in gappy turbulent velocity data"
authors:
- admin
- Scott A Socolofsky
date: "2018-Jan-23T00:00:00Z"
doi: "https://doi.org/10.1002/lom3.10223"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-11-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Limnology and Oceanography: Methods, 16(1)*: 1-21"
publication_short: ""

abstract: This paper deals with the problem of data interpolation in velocity time series measured by acoustic Doppler velocimeters and acoustic Doppler current profilers; the gap‐filled data are often used to determine turbulent kinetic energy (TKE) dissipation using Kolmogorov's inertial subrange scaling. For the latter to estimate dissipation accurately, it is important that the interpolation scheme preserves the attributes, both spectral slope and component magnitudes, of the true energy spectrum. We show that this goal can be achieved using the simple zeroth‐order sample and hold interpolation in situations where isolated data gaps, having durations shorter than the integral time scale of flow, occur. Its success is explained using the framework of stochastic autoregressive (AR) processes, which we also compare to the Langevin equation for the Lagrangian velocity of a turbulent flow field. We also demonstrate that linear interpolation is not appropriate because it can be interpreted as a nonstationary second order AR process, leading to erroneous conclusions for spectral slope and magnitude. When data dropouts occur in clusters, i.e., of durations longer than the integral time scale, we propose to use the first order AR process, of which sample and hold is its limiting case, for interpolation. The effectiveness of our proposal is tested and demonstrated with synthetic time series having a range of spectral slopes, from −7/6 to −8/3, and with experimental data measured in a turbulent channel flow. A comparison is also made with the more sophisticated proper orthogonal decomposition‐based interpolation. The paper ends with a step‐by‐step procedure on using the proposed method in applications.

# Summary. An optional shortened abstract.
summary: This paper deals with the problem of data interpolation in velocity time series measured by acoustic Doppler velocimeters and acoustic Doppler current profilers; the gap‐filled data are often used to determine turbulent kinetic energy (TKE) dissipation using Kolmogorov's inertial subrange scaling.

tags:
- Bubble plumes
- Large-eddy simulation
- Lagrangian Particle Tracking
- Two-way coupling
- Slip velocity
- Delta functions

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
