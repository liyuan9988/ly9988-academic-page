---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dueling Bandits with Qualitative Feedback"
authors: [Liyuan Xu, Junya Honda, Masashi Sugiyama]
date: 2019-07-26
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-17

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence, 2019"
publication_short: "AAAI2019"

abstract: "We formulate and study a novel multi-armed bandit problem called the qualitative dueling bandit (QDB) problem, where an agent observes not numeric but qualitative feedback by pulling each arm. We employ the same regret as the dueling bandit (DB) problem where the duel is carried out by comparing the qualitative feedback. Although we can naively use classic DB algorithms for solving the QDB problem, this reduction significantly worsens the performance—--actually, in the QDB problem, the probability that one arm wins the duel over another arm can be directly estimated without carrying out actual duels. In this paper 1, we propose such direct algorithms for the QDB problem. Our theoretical analysis shows that the proposed algorithms significantly outperform DB algorithms by incorporating the qualitative feedback, and experimental results also demonstrate vast improvement over the existing DB algorithms."

# Summary. An optional shortened abstract.
summary: ""

tags: [Bandit]
categories: [Machine Learning]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
 - name: AAAI
   url: https://www.aaai.org/ojs/index.php/AAAI/article/view/4496
 - name: ArXiv
   url: https://arxiv.org/abs/1809.05274
 - name: Qiita(Japanese)
   url: https://qiita.com/ly9988/items/c1704e9f19f6e89bbfe5

url_pdf: https://www.aaai.org/ojs/index.php/AAAI/article/view/4496/4374
url_code: 
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
