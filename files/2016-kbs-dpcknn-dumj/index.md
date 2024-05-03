---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Study on density peaks clustering based on k-nearest neighbors and principal component analysis"
authors:
- admin
- Shifei Ding
- Hongjie Jia
date: 2016-02-09
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2016-02-09

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Knowledge-Based Systems*"
# publication_short: ""

abstract: "Density peaks clustering (DPC) algorithm published in the US journal Science in 2014 is a novel clustering
algorithm based on density. It needs neither iterative process nor more parameters. However, original
algorithm only has taken into account the global structure of data, which leads to missing many clusters.
In addition, DPC does not perform well when data sets have relatively high dimension. Especially, DPC
generates wrong number of clusters of real-world data sets. In order to overcome the first problem, we
propose a density peaks clustering based on k nearest neighbors (DPC-KNN) which introduces the idea of
k nearest neighbors (KNN) into DPC and has another option for the local density computation. In order
to overcome the second problem, we introduce principal component analysis (PCA) into the model of
DPC-KNN and further bring forward a method based on PCA (DPC-KNN-PCA), which preprocesses highdimensional data. By experiments on synthetic data sets, we demonstrate the feasibility of our algorithms.
By experiments on real-world data sets, we compared this algorithm with k-means algorithm and spectral
clustering (SC) algorithm in accuracy. Experimental results show that our algorithms are feasible and
effective."

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
