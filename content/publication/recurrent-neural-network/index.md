---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Recurrent Neural Network Architecture Search for Geophysical Emulation"
authors: [Romit Maulik, Romain Egele, Bethany Lusch, Prasanna Balaprakash]
date: 2020-04-24T21:05:09-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:05:09-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Developing surrogate geophysical models from data is a key research topic in atmospheric andoceanic modeling because of the large computational costs associated with numerical simulationmethods. Researchers have started applying a wide range of machine learning models, in particularneural networks, to geophysical data for forecasting without these constraints. However, constructingneural networks for forecasting such data is nontrivial and often requires trial and error. To that end,we focus on developing proper-orthogonal-decomposition-based long short-term memory networks(POD-LSTMs). We develop a scalable neural architecture search for generating stacked LSTMs toforecast temperature in the NOAA Optimum Interpolation Sea-Surface Temperature data set. Ourapproach identifies POD-LSTMs that are superior to manually designed variants and baseline time-series prediction methods. We also assess the scalability of different architecture search strategieson up to 512 Intel Knights Landing nodes of the Theta supercomputer at the Argonne Leadership Computing Facility."

# Summary. An optional shortened abstract.
summary: ""

tags: [LSTMs, AutoML, Emulators, Geophysics]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2004.10928.pdf
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
