---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Importance Weighted Kernel Bayes’ Rule
"
subtitle: ""
summary: ""
authors: [Liyuan Xu, Yutian Chen, Arnaud Doucet, Arthur Gretton]
tags: ["Bayes Learning"]
categories: [Machine Learning]
date: 2022-07-17
lastmod: 2022-07-17
featured: false
draft: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract: "We study a nonparametric approach to Bayesian computation via feature means, where the expectation of prior features is updated to yield expected posterior features, based on regression from kernel or neural net features of the observations. All quantities involved in the Bayesian update are learned from observed data, making the method entirely model-free. The resulting algorithm is a novel instance of a kernel Bayes’ rule (KBR). Our approach is based on importance weighting, which results in superior numerical stability to the existing approach to KBR, which requires operator inversion. We show the convergence of the estimator using a novel consistency analysis on the importance weighting estimator in the infinity norm. We evaluate our KBR on challenging synthetic benchmarks, including a filtering problem with a state-space model involving high dimensional image observations. The proposed method yields uniformly better empirical performance than the existing KBR, and competitive performance with other competing methods. We evaluate our KBR on challenging synthetic benchmarks, including a filtering problem with a state-space model involving high dimensional image observations. The proposed method yields uniformly better empirical performance than the existing KBR, and competitive performance with other competing methods."

links:
 - name: JMLR
   url: https://proceedings.mlr.press/v162/xu22a.html
url_pdf: https://proceedings.mlr.press/v162/xu22a/xu22a.pdf


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

url_code: https://github.com/liyuan9988/IWKernelBayesRule
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
