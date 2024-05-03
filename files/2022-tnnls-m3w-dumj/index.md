---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "M3W: Multistep Three-Way Clustering"
authors:
- admin
- Jingqi Zhao
- Jiarui Sun
- Yongquan Dong
date: 2022-09-17
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-17

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Networks and Learning Systems*"
# publication_short: ""

abstract: "Three-way clustering has been an active research
 topic in the field of cluster analysis in recent years. Some
 efforts are focused on the technique due to its feasibility and
 rationality. We observe, however, that the existing three-way
 clustering algorithms struggle to obtain more information and
 limit the fault tolerance excessively. Moreover, although the
 one-step three-way allocation based on a pair of fixed, global
 thresholds is the most straightforward way to generate the
 three-way cluster representations, the clusters derived from a
 pair of global thresholds cannot exactly reveal the inherent
 clustering structure of the dataset, and the threshold values are
 often difficult to determine beforehand. Inspired by sequential
 three-way decisions, we propose an algorithm, called multistep
 three-way clustering (M3W), to address these issues. Specifically,
 we first use a progressive erosion strategy to construct a multilevel
 structure of data, so that lower levels (or external layers)
 can gather more available information from higher levels (or
 internal layers). Then, we further propose a multistep three-way
 allocation strategy, which sufficiently considers the neighborhood
 information of every eroded instance. We use the allocation
 strategy in combination with the multilevel structure to ensure
 that more information is gradually obtained to increase the
 probability of being assigned correctly, capturing adaptively the
 inherent clustering structure of the dataset. The proposed algorithm is compared with eight competitors using 18 benchmark datasets. Experimental results show that M3W achieves superior performance, verifying its advantages and effectiveness."

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
url_code: https://github.com/Du-Team/M3W
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
