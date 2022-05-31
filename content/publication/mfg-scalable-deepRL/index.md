---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Scalable Deep Reinforcement Learning Algorithms for Mean Field Games"
authors: [Mathieu Laurière, Sarah Perrin, Sertan Girgin, Paul Muller, Ayush Jain, Theophile Cabannes, 
          Georgios Piliouras, Julien Pérolat, Romuald Élie, Olivier Pietquin, Matthieu Geist]
date: 2022-01-28T16:48:05+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T16:48:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ICML 2022"
publication_short: ""

abstract: "
Mean Field Games (MFGs) have been introduced to efficiently approximate games with very large populations of strategic 
agents. Recently, the question of learning equilibria in MFGs has gained momentum, particularly using model-free 
reinforcement learning (RL) methods. One limiting factor to further scale up using RL is that existing algorithms to 
solve MFGs require the mixing of approximated quantities such as strategies or -values. This is non-trivial in the case 
of non-linear function approximation that enjoy good generalization properties, e.g. neural networks. We propose two 
methods to address this shortcoming. The first one learns a mixed strategy from distillation of historical data into a 
neural network and is applied to the Fictitious Play algorithm. The second one is an online mixing method based on 
regularization that does not require memorizing historical data or previous estimates. It is used to extend Online 
Mirror Descent. We demonstrate numerically that these methods efficiently enable the use of Deep RL algorithms to 
solve various MFGs. In addition, we show that these methods outperform SotA baselines from the literature."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2203.11973.pdf
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
