---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Similarity-based Classification: Connecting Similarity Learning to Binary Classification"
authors: [Han Bao, Takuya Shimada, Liyuan Xu, Issei Sato, Masashi Sugiyama]
date: 2020-06-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-11

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In real-world classification problems, pairwise supervision (i.e., a pair of patterns with a binary label indicating whether they belong to the same class or not) can often be obtained at a lower cost than ordinary class labels. Similarity learning is a general framework to utilize such pairwise supervision to elicit useful representations by inferring the relationship between two data points, which encompasses various important preprocessing tasks such as metric learning, kernel learning, graph embedding, and contrastive representation learning. Although elicited representations are expected to perform well in downstream tasks such as classification, little theoretical insight has been given in the literature so far. In this paper, we reveal that a specific formulation of similarity learning is strongly related to the objective of binary classification, which spurs us to learn a binary classifier without ordinary class labels---by fitting the product of real-valued prediction functions of pairwise patterns to their similarity. Our formulation of similarity learning does not only generalize many existing ones, but also admits an excess risk bound showing an explicit connection to classification. Finally, we empirically demonstrate the practical usefulness of the proposed method on benchmark datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Weak Supervision", "Preprints"]
categories: ["Machine Learning"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: ArXiv
  url: https://arxiv.org/abs/2006.06207
url_pdf: https://arxiv.org/pdf/2006.06207.pdf
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
