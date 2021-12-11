---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Reduced-order modeling of advection-dominatedsystems with recurrent neural networks andconvolutional autoencoders"
authors: [Romit Maulik, Bethany Lusch, Prasanna Balaprakash]
date: 2020-02-04T21:34:17-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:34:17-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "A common strategy for the dimensionality reduction of nonlinear partial dif-ferential equations relies on the use of the proper orthogonal decomposition(POD) to identify a reduced subspace and the Galerkin projection for evolv-ing  dynamics  in  this  reduced  space.   However,  advection-dominated  PDEsare represented poorly by this methodology since the process of truncationdiscards important interactions between higher-order modes during time evo-lution.  In this study, we demonstrate that an encoding using convolutionalautoencoders (CAEs) followed by a reduced-space time evolution by recur-rent neural networks overcomes this limitation effectively.  We demonstratethat a truncated system of only two latent-space dimensions can reproduce asharp advecting shock profile for the viscous Burgers equation with very lowviscosities, and a twelve-dimensional latent space can recreate the evolutionof the inviscid shallow water equations.  Additionally,  the proposed frame-work is extended to a parametric reduced-order model by directly embeddingparametric information into the latent space to detect trends in system evo-lution.  Our results show that these advection-dominated systems are moreamenable  to  low-dimensional  encoding  and  time  evolution  by  a  CAE  andrecurrent neural network combination than the POD Galerkin technique."

# Summary. An optional shortened abstract.
summary: ""

tags: [ROMs, Autoencoders, Recurrent neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2002.00470.pdf
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
