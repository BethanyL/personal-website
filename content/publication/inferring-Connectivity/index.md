---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inferring Connectivity in Networked Dynamical Systems: Challenges Using Granger Causality"
authors: [Bethany Lusch, Pedro D. Maia, J. Nathan Kutz]
date: 2016-09-27T23:04:44-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-02T23:04:44-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Physical Review"
publication_short: ""

abstract: "Determining the interactions and causal relationships between nodes in an unknown networked dynamical system from measurement data alone is a challenging, contemporary task across the physical, biological, and engineering sciences. Statistical methods, such as the increasingly popular Granger causality, are being broadly applied for data-driven discovery of connectivity in fields from economics to neuroscience. A common version of the algorithm is called pairwise-conditional Granger causality, which we systematically test on data generated from a nonlinear model with known causal network structure. Specifically, we simulate networked systems of Kuramoto oscillators and use the Multivariate Granger Causality Toolbox to discover the underlying coupling structure of the system. We compare the inferred results to the original connectivity for a wide range of parameters such as initial conditions, connection strengths, community structures, and natural frequencies. Our results show a significant systematic disparity between the original and inferred network, unless the true structure is extremely sparse or dense. Specifically, the inferred networks have significant discrepancies in the number of edges and the eigenvalues of the connectivity matrix, demonstrating that they typically generate dynamics which are inconsistent with the ground truth. We provide a detailed account of the dynamics for the Erdős-Rényi network model due to its importance in random graph theory and network science. We conclude that Granger causal methods for inferring network structure are highly suspect and should always be checked against a ground truth model. The results also advocate the need to perform such comparisons with any network inference method since the inferred connectivity results appear to have very little to do with the ground truth system. "

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

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: https://pubmed.ncbi.nlm.nih.gov/27739857/
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
