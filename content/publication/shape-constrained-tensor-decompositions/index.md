---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Shape Constrained Tensor Decompositions usingSparse Representations in Over-Complete Libraries"
authors: [Bethany Lusch, Eric C. Chi, J. Nathan Kutz]
date: 2016-08-16T22:20:30-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T22:20:30-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2019 IEEE International Conference on Data Science and Advanced Analytics"
publication_short: "DSAA"

abstract: "We consider N-way data arrays and low-rank tensor factorizations  where  the  time  mode  is  coded  as  a  sparse  linear combination of temporal elements from an over-complete library. Our  method,  Shape  Constrained  Tensor  Decomposition  (SCTD) is based upon the CANDECOMP/PARAFAC (CP) decomposition which   produces r-rank   approximations   of   data   tensors   via outer  products  of  vectors  in  each  dimension  of  the  data.  By constraining  the  vector  in  the  temporal  dimension  to  known analytic  forms  which  are  selected  from  a  large  set  of  candidate functions, more readily interpretable decompositions are achieved and  analytic  time  dependencies  discovered.  The  SCTD  method circumvents  traditional flattening techniques  where  an N-way array  is  reshaped  into  a  matrix  in  order  to  perform  a  singular value  decomposition.  A  clear  advantage  of  the  SCTD  algorithmis  its  ability  to  extract  transient  and  intermittent  phenomena which is often difficult for SVD-based methods. We motivate the SCTD  method  using  several  intuitively  appealing  results  before applying  it  on  a  number  of  high-dimensional,  real-world  datasets  in  order  to  illustrate  the  efficiency  of  the  algorithm  inextracting  interpretable  spatio-temporal  modes.  With  the  rise of  data-driven  discovery  methods,  the  decomposition  proposed provides  a  viable  technique  for  analyzing  multitudes  of  data  in a  more  comprehensible  fashion."

# Summary. An optional shortened abstract.
summary: ""

tags: [machine learning, tensor decomposition, multiway arrays, multilinear algebra, higher-order singular value decomposition (HOSVD), over-complete libraries, sparse regression]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1608.04674.pdf
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
