---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Using recurrent neural networks for nonlinear component computation in advection-dominated reduced-order models"
authors: [Romit Maulik,Vishwas Rao, Sandeep Madireddy, Bethany Lusch, Prasanna Balaprakash]
date: 2019-11-01T22:34:18-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T22:34:18-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Second Workshop on Machine Learning and the Physical Sciences at NeurIPS"
publication_short: ""

abstract: "Rapid simulations of advection-dominated problems are vital for multiple engineering and geophysical applications. In this paper, we present a long short-term memory neural network to approximate the nonlinear component of the reduced-order model (ROM) of an advection-dominated partial differential equation. This is motivated by the fact that the nonlinear term is the most expensive component of a successful ROM. For our approach, we utilize a Galerkin projection to isolate the linear and the transient components of the dynamical system and then use discrete empirical interpolation to generate training data for supervised learning. We note that the numerical time-advancement and linear-term computation of the system ensures a greater preservation of physics than does a process that is fully modeled. Our results show that the proposed framework recovers transient dynamics accurately without nonlinear term computations in full-order space and represents a cost-effective alternative to solely equation-based ROMs."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.researchgate.net/publication/335975841_Using_recurrent_neural_networks_for_nonlinear_component_computation_in_advection-dominated_reduced-order_models
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
