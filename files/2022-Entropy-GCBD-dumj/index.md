---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Grid-Based Clustering Using Boundary Detection"
authors: 
- admin
- Fuyu Wu
date: 2022-11-04
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-04

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Entropy"
publication_short: ""

abstract: "Clustering can be divided into five categories: partitioning, hierarchical, model-based, density-based, and grid-based algorithms. Among them, grid-based clustering is highly efficient in handling spatial data. However, the traditional grid-based clustering algorithms still face many problems: (1) Parameter tuning: density thresholds are difficult to adjust; (2) Data challenge: clusters with overlapping regions and varying densities are not well handled. We propose a new gridbased clustering algorithm named GCBD that can solve the above problems. Firstly, the density estimation of nodes is defined using the standard grid structure. Secondly, GCBD uses an iterative boundary detection strategy to distinguish core nodes from boundary nodes. Finally, two clustering strategies are combined to group core nodes and assign boundary nodes. Experiments on 18 datasets demonstrate that the proposed algorithm outperforms 6 grid-based competitors."

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
url_code: https://github.com/Du-Team/GCDB
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
