---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Music Artist Classification with Convolutional Recurrent Neural Networks"
authors: 
- admin
- Zain Nasrullah


#date: 2019-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-18T08:05:15+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Joint Conference on Neural Networks (IJCNN)*"
publication_short: ""

abstract: "Previous attempts at music artist classification use frame level audio features which summarize frequency content within short intervals of time. Comparatively, more recent music information retrieval tasks take advantage of temporal structure in audio spectrograms using deep convolutional and recurrent models. This paper revisits artist classification with this new framework and empirically explores the impacts of incorporating temporal structure in the feature representation. To this end, an established classification architecture, a Convolutional Recurrent Neural Network (CRNN), is applied to the artist20 music artist identification dataset under a comprehensive set of conditions. These include audio clip length, which is a novel contribution in this work, and previously identified considerations such as dataset split and feature level. Our results improve upon baseline works, verify the influence of the producer effect on classification performance and demonstrate the trade-offs between audio length and training set size. The best performing model achieves an average F1 score of 0.937 across three independent trials which is a substantial improvement over the corresponding baseline under similar conditions. Additionally, to showcase the effectiveness of the CRNN's feature extraction capabilities, we visualize audio samples at the model's bottleneck layer demonstrating that learned representations segment into clusters belonging to their respective artists."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, machine learning]
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
  url: https://arxiv.org/abs/1901.04555
  icon_pack: ai
  icon: arxiv
  
url_pdf: papers/19-ijcnn-music.pdf
url_code: https://github.com/ZainNasrullah/music-artist-classification-crnn
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
