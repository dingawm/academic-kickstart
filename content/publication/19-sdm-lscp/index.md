---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Locally Selective Combination in Parallel Outlier Ensembles"
authors: 
- Yue Zhao
- Zain Nasrullah
- Maciej K. Hryniewicki
- Zheng Li


#date: 2019-05
doi: "10.1137/1.9781611975673.66"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-05-22T08:05:15+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*SIAM International Conference on Data Mining (SDM)*"
publication_short: ""

abstract: "In unsupervised outlier ensembles, the absence of ground truth makes the combination of base outlier detectors a challenging task. 
Specifically, existing parallel outlier ensembles lack a reliable way of selecting competent base detectors, 
affecting accuracy and stability, during model combination. In this paper, 
we propose a framework—called Locally Selective Combination in Parallel Outlier Ensembles (LSCP)--
which addresses the issue by defining a local region around a test instance using the consensus of its nearest neighbors in randomly selected feature subspaces. 
The top-performing base detectors in this local region are selected and combined as the model's final output. 
Four variants of the LSCP framework are compared with seven widely used parallel frameworks. 
Experimental results demonstrate that one of these variants, LSCP_AOM, consistently outperforms baselines on the majority of twenty real-world datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: [outlier detection, Python]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: SIAM epubs
  url: https://epubs.siam.org/doi/abs/10.1137/1.9781611975673.66
  
url_pdf: papers/19-sdm-lscp.pdf
url_code: https://github.com/yzhao062/LSCP
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
