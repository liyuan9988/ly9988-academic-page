---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Alternate Estimation of a Classifier and The Class-Prior from Positive and Unlabeled Data"
subtitle: ""
summary: ""
authors: [Masahiro Kato, Liyuan Xu, Gang Niu, Masashi Sugiyama]
tags: [Weak Supervision, Preprints]
categories: [Machine Learning]
date: 2018-09-15
lastmod: 2018-09-15
featured: false
draft: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

abstract: "We consider a problem of learning a binary classifier only from positive data and unlabeled data (PU learning) and estimating the class-prior in unlabeled data under the case-control scenario. Most of the recent methods of PU learning require an estimate of the class-prior probability in unlabeled data, and it is estimated in advance with another method. However, such a two-step approach which first estimates the class prior and then trains a classifier may not be the optimal approach since the estimation error of the class-prior is not taken into account when a classifier is trained. In this paper, we propose a novel unified approach to estimating the class-prior and training a classifier alternately. Our proposed method is simple to implement and computationally efficient. Through experiments, we demonstrate the practical usefulness of the proposed method."

links:
 - name: ArXiv
   url: https://arxiv.org/abs/1809.05710
url_pdf: https://arxiv.org/pdf/1809.05710.pdf


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
