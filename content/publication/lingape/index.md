---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Fully Adaptive Algorithm for Pure Exploration in Linear Bandits"
authors: [Liyuan Xu, Junya Honda, Masashi Sugiyama]
date: 2018-04-26
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-04-26

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the Twenty-First International Conference on Artificial Intelligence and Statistics"
publication_short: "AISTATS2018"

abstract: "We propose the first fully-adaptive algorithm for pure exploration in linear bandits—the task to find the arm with the largest expected reward, which depends on an unknown parameter linearly. While existing methods partially or entirely fix sequences of arm selections before observing rewards, our method adaptively changes the arm selection strategy based on past observations at each round. We show our sample complexity matches the achievable lower bound up to a constant factor in an extreme case. Furthermore, we evaluate the performance of the methods by simulations based on both synthetic setting and real-world data, in which our method shows vast improvement over existing ones."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bandit"]
categories: ["Machine Learning"]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: PMLR
   url: http://proceedings.mlr.press/v84/xu18d.html
 - name: ArXiv
   url: https://arxiv.org/abs/1710.05552
 - name: Qiita(Japanese)
   url: https://qiita.com/ly9988/items/3f4090bccab536f4b994
   

url_pdf: http://proceedings.mlr.press/v84/xu18d/xu18d.pdf
url_code: https://github.com/liyuan9988/LinGapE
url_dataset:
url_poster: poster.pdf
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
