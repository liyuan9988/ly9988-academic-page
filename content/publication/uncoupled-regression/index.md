---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Uncoupled Regression from Pairwise Comparison Data"
authors: [Liyuan Xu, Junya Honda, Gang Niu, Masashi Sugiyama]
date: 2019-12-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Advances in Neural Information Processing Systems 32"
publication_short: "NeurIPS2019"

abstract: "Uncoupled regression is the problem to learn a model from unlabeled data and the set of target values while the correspondence between them is unknown. Such a situation arises in predicting anonymized targets that involve sensitive information, e.g., one's annual income. Since existing methods for uncoupled regression often require strong assumptions on the true target function, and thus, their range of applications is limited, we introduce a novel framework that does not require such assumptions in this paper. Our key idea is to utilize \emph{pairwise comparison data, which consists of pairs of unlabeled data that we know which one has a larger target value. Such pairwise comparison data is easy to collect, as typically discussed in the learning-to-rank scenario, and does not break the anonymity of data. We propose two practical methods for uncoupled regression from pairwise comparison data and show that the learned regression model converges to the optimal model with the optimal parametric convergence rate when the target variable distributes uniformly. Moreover, we empirically show that for linear models the proposed methods are comparable to ordinary supervised regression with labeled data."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Weak Supervision"]
categories: ["Machine Learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
 - name: NeurIPS
   url: http://papers.neurips.cc/paper/8654-uncoupled-regression-from-pairwise-comparison-data
 - name: ArXiv
   url: https://arxiv.org/abs/1905.13659

url_pdf: http://papers.nips.cc/paper/8654-uncoupled-regression-from-pairwise-comparison-data.pdf
url_code: https://github.com/liyuan9988/UncoupledRegressionComparison/
url_dataset:
url_poster: NIPS2019_poster.pdf
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
