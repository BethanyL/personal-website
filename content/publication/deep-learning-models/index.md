---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Learning Models for Global CoordinateTransformations that Linearize PDEs"
authors: [Criag Gin, Bethany Lusch, Steven L. Brunton, J. Nathan Kutz]
date: 2019-11-11T21:56:48-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:56:48-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We develop a deep autoencoder architecture that can be used to find a coordinate trans-formation which turns a nonlinear PDE into a linear PDE. Our architecture is motivatedby the linearizing transformations provided by the Cole-Hopf transform for Burgers equa-tion and the inverse scattering transform for completely integrable PDEs. By leveraginga  residual  network  architecture,  a  near-identity  transformation  can  be  exploited  to  en-code intrinsic coordinates in which the dynamics are linear. The resulting dynamics aregiven by a Koopman operator matrixK. The decoder allows us to transform back to theoriginal coordinates as well. Multiple time step prediction can be performed by repeatedmultiplication by the matrixKin the intrinsic coordinates. We demonstrate our methodon  a  number  of  examples,  including  the  heat  equation  and  Burgers  equation,  as  wellas the substantially more challenging Kuramoto-Sivashinsky equation, showing that ourmethod provides a robust architecture for discovering interpretable, linearizing transformsfor nonlinear PDEs"

# Summary. An optional shortened abstract.
summary: ""

tags: [Koopman theory, deep neural nets, residual networks, linearizing transforms, Cole-Hopf transform]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1911.02710.pdf
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
