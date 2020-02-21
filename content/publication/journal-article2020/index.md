---
title: "Kinetic-based Multiphase Flow Simulation"
authors:
- admin
- Daoming Liu
- Mathieu Desbrun
- Jin Huang
- Xiaopei Liu
date: "2020-02-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Visualization and Computer Graphics"
publication_short: "TVCG"

abstract: Multiphase flows exhibit a large realm of complex behaviors such as bubbling, glugging, wetting, and splashing which emerge from air-water and water-solid interactions. Current fluid solvers in graphics have demonstrated remarkable success in reproducing each of these visual effects, but none have offered a model general enough to capture all of them concurrently. In contrast, computational fluid dynamics have developed very general approaches to multiphase flows, typically based on kinetic models. Yet, in both communities, there is dearth of methods that can simulate density ratios and Reynolds numbers required for the type of challenging real-life simulations that movie productions strive to digitally create, such as air-water flows. In this paper, we propose a kinetic model of the coupling of the Navier-Stokes equations with a conservative phase-field equation, and provide a series of numerical improvements over existing kinetic-based approaches to offer a general multiphase flow solver. The resulting algorithm is embarrassingly parallel, conservative, far more stable than current solvers even for real-life conditions, and general enough to capture the typical multiphase flow behaviors. Various simulation results are presented, including comparisons to both previous work and real footage, to highlight the advantages of our new method.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Visualization and Computer Graphics (TVCG), accepted for publication, 2020. (CCF-A journal)

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8986688
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
url_video: 'https://www.youtube.com/watch?v=-ArL7AD9mGM'

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

 

