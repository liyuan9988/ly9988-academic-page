---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Polynomial-time Algorithms for Multiple-arm Identification with Full-bandit Feedback"
authors: [Yuko Kuroki, Liyuan Xu, Atsushi Miyauchi, Junya Honda, Masashi Sugiyama]
date: 2019-09-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Accepted to Neural Computation"
publication_short: "Accepted to NeCo2020"

abstract: "We study the problem of stochastic combinatorial pure exploration (CPE), where an agent sequentially pulls a set of single arms (a.k.a. a super arm) and tries to find the best super arm. Among a variety of problem settings of the CPE, we focus on the full-bandit setting, where we cannot observe the reward of each single arm, but only the sum of the rewards. Although we can regard the CPE with full-bandit feedback as a special case of pure exploration in linear bandits, an approach based on linear bandits is not computationally feasible since the number of super arms may be exponential. In this paper, we first propose a polynomial-time bandit algorithm for the CPE under general combinatorial constraints and provide an upper bound of the sample complexity. Second, we design an approximation algorithm for the 0-1 quadratic maximization problem, which arises in many bandit algorithms with confidence ellipsoids. Based on our approximation algorithm, we propose novel bandit algorithms for the top-k selection problem, and prove that our algorithms run in polynomial time. Finally, we conduct experiments on synthetic and real-world datasets, and confirm the validity of our theoretical analysis in terms of both the computation time and the sample complexity."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bandit"]
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
  url: https://arxiv.org/abs/1902.10582

url_pdf: https://arxiv.org/pdf/1902.10582.pdf
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
