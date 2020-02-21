---
title: "Continuous-Scale Kinetic Fluid Simulation"
authors:
- admin
- Kai Bai
- Xiaopei Liu
date: "2018-07-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Visualization and Computer Graphics"
publication_short: "TVCG"

abstract: Kinetic approaches, i.e., methods based on the lattice Boltzmann equations, have long been recognized as an appealing alternative for solving incompressible Navier-Stokes equations in computational fluid dynamics. However, such approaches have not been widely adopted in graphics mainly due to the underlying inaccuracy, instability and inflexibility. In this paper, we try to tackle these problems in order to make kinetic approaches practical for graphical applications. To achieve more accurate and stable simulations, we propose to employ the non-orthogonal central-moment-relaxation model, where we develop a novel adaptive relaxation method to retain both stability and accuracy in turbulent flows. To achieve flexibility, we propose a novel continuous-scale formulation that enables samples at arbitrary resolutions to easily communicate with each other in a more continuous sense and with loose geometrical constraints, which allows efficient and adaptive sample construction to better match the physical scale. Such a capability directly leads to an automatic sample construction which generates static and dynamic scales at initialization and during simulation, respectively. This effectively makes our method suitable for simulating turbulent flows with arbitrary geometrical boundaries. Our simulation results with applications to smoke simulations show the benefits of our method, with comparisons for justification and verification.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Visualization and Computer Graphics (TVCG), accepted for publication, 2018. (CCF-A journal)

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8419266
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
url_video: 'https://www.youtube.com/watch?v=vgr_qR761y0&t=6s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: 
---

 

