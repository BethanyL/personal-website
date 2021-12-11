---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accelerating RANS Simulations Using A Data-Driven Framework for Eddy-Viscosity Emulation"
authors: [Romit Maulik, Himanshu Sharma, Saumil Patel, Bethany Lusch, Elise Jennings]
date: 2020-05-21T22:13:47-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T22:13:47-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Reynolds-averaged Navier-Stokes (RANS) equations for steady-state assessment of incompressibleturbulent flows remain the workhorse for practical computational fluid dynamics (CFD) applications,and improvements in speed or accuracy have the potential to affect a diverse range of sectors. Weintroduce a machine learning framework for the acceleration of RANS to predict steady-state turbulenteddy viscosities, given the initial conditions. This surrogate model for the turbulent eddy viscosityis assessed for parametric interpolation, while numerically solving for the pressure and velocityequations to steady state, thus representing a framework that is hybridized with machine learning. Weachieve accurate steady-state results with a significant reduction in solution time when compared tothose obtained by the Spalart-Allmaras one-equation model. Most notably the proposed methodologyallows for considerably larger relaxation factors for the steady-state velocity and pressure solvers. Ourassessments are made for a backward-facing step with considerable mesh anisotropy and separationto represent a practical CFD application. For test experiments with varying inlet velocity conditions,we see time-to-solution reductions around a factor of 5. Similar results are obtained for a surrogatemodeling strategy that generalizes across varying step heights. The proposed framework representsan excellent opportunity for the rapid exploration of large parameter spaces that prove prohibitivewhen utilizing turbulence closure models with multiple coupled partial differential equations."

# Summary. An optional shortened abstract.
summary: ""

tags: [fluid dynamics, computational physics]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1910.10878.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
