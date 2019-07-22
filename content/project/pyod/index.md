---
title: Python Outlier Detection Toolbox
summary: PyOD--A Python Toolbox for Scalable Outlier Detection (Anomaly Detection)
tags:
- Machine Learning
date: "2018-05-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
#  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
#- icon: copy
#  icon_pack: fab
#  name: Paper
#  url: papers/19-jmlr-pyod.pdf
#  link: https://github.com/yzhao062/pyod
  
#- icon: github
#  icon_pack: fab
#  name: GitHub
#  url: https://github.com/yzhao062/pyod

links:
- name: Doc
  url: https://pyod.readthedocs.io/

url_code: "https://github.com/yzhao062/pyod"
url_pdf: "papers/19-jmlr-pyod.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

PyOD is the most popular detection toolbox with more than 2,000 GitHub stars and 80,000 downloads on PyPI. 
Its accompanied paper is published in Journal of Machine Learning Research (JMLR) .

* JMLR Link: http://www.jmlr.org/papers/v20/19-011.html
* Github : https://github.com/yzhao062/pyod 
* PyPI: https://pypi.org/project/pyod
* Documentation: https://pyod.readthedocs.io
* Interactive Jupyter Notebooks: https://mybinder.org/v2/gh/yzhao062/pyod/master

PyOD is a comprehensive and efficient Python toolkit to identify outlying objects in multivariate data. 
This exciting yet challenging field is commonly referred as  Outlier Detection or Anomaly Detection. Since 2017, PyOD has been successfully used in various academic researches and commercial products. 
It is featured for:

* Unified APIs, detailed documentation, and interactive examples across various algorithms.
* Advanced models, including Neural Networks/Deep Learning and Outlier Ensembles.
* Optimized performance with JIT and parallelization when possible, using numba and joblib.
* Compatible with both Python 2 & 3.

PyOD toolkit consists of three major groups of functionalities: 

1. outlier detection algorithms; 
2. outlier ensemble frameworks and 
3. outlier detection utility functions. 

Comparison of all implemented models are made available below:

![PyOD All Models](/img/pyod-all-models.jpg)
