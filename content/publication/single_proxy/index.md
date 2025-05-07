---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Kernel Single Proxy Control for Deterministic Confounding"
authors: [Liyuan Xu, Arthur Gretton]
date: 2025-05-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Artificial Intelligence and Statistics"
publication_short: "AISTSTS2025"

abstract: "We consider the problem of causal effect estimation with an unobserved confounder, where we observe a single proxy variable that is associated with the confounder. Although it has been shown that the recovery of an average causal effect is impossible in general from a single proxy variable, we show that causal recovery is possible if the outcome is generated deterministically. This generalizes existing work on causal methods with a single proxy variable to the continuous treatment setting. We propose two kernel-based methods for this setting: the first based on the two-stage regression approach, and the second based on a maximum moment restriction approach. We prove that both approaches can consistently estimate the causal effect, and we empirically demonstrate that we can successfully recover the causal effect on challenging synthetic benchmarks."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Causal Learning"]
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
- name: Openreview
  url: https://openreview.net/forum?id=XP7AUhVhhu
url_pdf: https://openreview.net/attachment?id=XP7AUhVhhu&name=pdf
url_code: https://github.com/liyuan9988/KernelSingleProxy
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
