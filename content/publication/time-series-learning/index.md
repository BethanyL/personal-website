---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Time-series learning of latent-space dynamics for reduced-order model closure"
authors: [Romit Maulik, Arvind Mohan, Bethany Lusch, Sandeep Madireddy, Prasanna Balaprakash, Daniel Livescu]
date: 2020-01-27T21:25:58-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T21:25:58-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Physica D: Nonlinear Phenomena"
publication_short: ""

abstract: "We study the performance of long short-term memory networks (LSTMs) and neural ordinarydifferential equations (NODEs) in learning latent-space representations of dynamical equations for anadvection-dominated problem given by the viscous Burgers equation. Our formulation is devised in anonintrusive manner with an equation-free evolution of dynamics in a reduced space with the latterbeing obtained through a proper orthogonal decomposition. In addition, we leverage the sequentialnature of learning for both LSTMs and NODEs to demonstrate their capability for closure in systemsthat are not completely resolved in the reduced space. We assess our hypothesis for two advection-dominated problems given by the viscous Burgers equation. We observe that both LSTMs and NODEsare able to reproduce the effects of the absent scales for our test cases more effectively than doesintrusive dynamics evolution through a Galerkin projection. This result empirically suggests that time-series learning techniques implicitly leverage a memory kernel for coarse-grained system closure asis suggested through the Mori–Zwanzig formalism."

# Summary. An optional shortened abstract.
summary: ""

tags: [ROMs, LSTMs, Neural ODEs, Closures]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://public.lanl.gov/livescu/frames/Maulik_etal_PhysicaD20.pdf
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
