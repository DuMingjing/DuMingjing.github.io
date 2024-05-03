---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ROBP: A robust border-peeling clustering using Cauchy kernel"
authors:
- admin
- Ru Wang
- Ru Ji
- Xia Wang
- Yongquan Dong
date: 2021-05-04
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-05-04

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Sciences*"
# publication_short: ""

abstract: "Recently a novel density-based clustering algorithm, namely, border-peeling (BP) clustering algorithm, is proposed to group data by iteratively identifying border points and peeling off them until separable areas of data remain. The BP clustering is able to correctly
recognize the true structure of clusters and automatically detect the outliers on several test
cases. However, there are some drawbacks in BP, and these may hinder its widespread
application. The BP clustering might yield bad results on datasets with non-uniformlydistributed clusters. Especially, the BP clustering tends to over-partition the data with complex shape. To overcome these defects, a robust border-peeling clustering algorithm
(named as ROBP) is proposed in this paper. Our method improves the BP clustering algorithm from two aspects: density influence (i.e. density estimation) and linkage criterion
(i.e. association strategy). In density estimation, we use Cauchy kernel with longer tails
instead of Gaussian kernel in the local scaling function, and further propose a kernel density estimator, i.e., the density estimator based on Cauchy kernel. It can calculate quickly
and accurately the density influence value of each point. In association strategy, we design
a linkage criterion based on the shared neighborhood information. The linkage criterion
can create some links between peeled border points and their neighboring peeled border
points, in order to avoid over-segmentation of the clusters. We integrate the proposed linkage criterion and the uni-directional association strategy, and further propose a bidirectional association strategy. In experiments, we compare ROBP with 7 representative
density-based clustering (or hierarchical clustering) algorithms, including BP, DBSCAN,
HDBSCAN, density peak (DP) clustering, DPC-KNN, DPC-DBFN and McDPC, on 8 synthetic
datasets and 11 real-world datasets. Results show that the proposed algorithm outperforms 7 competitors in most cases. Moreover, we compare the robustness of ROBP and
BP, and evaluate their running time. Experimental results indicate that ROBP is much more
robust and reliable, as well as it is competitive to BP in computational efficiency."

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
url_code: https://github.com/Du-Team/ROBP
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
