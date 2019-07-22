---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SynC: A Unified Framework for Generating Synthetic Population with Gaussian Copula"
authors: 
- Colin Wan
- Zheng Li
- admin


#date: 2019-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-22T08:05:15+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Arxiv (under submission)*"
publication_short: ""

abstract: "Synthetic population generation is the process of combining multiple socioeonomic and demographic datasets from various sources and at different granularity, and downscaling them to an individual level. Although it is a fundamental step for many data science tasks, an efficient and standard framework is absent. In this study, we propose a multi-stage framework called SynC (Synthetic Population via Gaussian Copula) to fill the gap. SynC first removes potential outliers in the data and then fits the filtered data with a Gaussian copula model to correctly capture dependencies and marginal distributions of sampled survey data. Finally, SynC leverages neural networks to merge datasets into one and then scales them accordingly to match the marginal constraints. We make four key contributions in this work: 1) propose a novel framework for generating individual level data from aggregated data sources by combining state-of-the-art machine learning and statistical techniques, 2) design a metric for validating the accuracy of generated data when the ground truth is hard to obtain, 3) demonstrate its effectiveness with the Canada National Census data and presenting two real-world use cases where datasets of this nature can be leveraged by businesses, and 4) release an easy-to-use framework implementation for reproducibility."

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
- name: Arxiv
  url: https://arxiv.org/abs/1904.07998
  icon_pack: ai
  icon: arxiv
  
url_pdf: papers/19-preprint-sync.pdf
url_code: https://github.com/winstonll/SynC
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
