---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Concave Utility Reinforcement Learning: the Mean-field Game viewpoint"
authors: [Matthieu Geist, Julien Pérolat, Mathieu Laurière, Romuald Elie, Sarah Perrin, Olivier Bachem, Rémi Munos, Olivier Pietquin]
date: 2020-07-28T16:48:05+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T16:48:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Under review."
publication_short: ""

abstract: "Concave Utility Reinforcement Learning (CURL) extends RL from linear to concave utilities in the
occupancy measure induced by the agent’s policy. This encompasses not only RL but also imitation
learning and exploration, among others. Yet, this more general paradigm invalidates the classical Bellman
equations, and calls for new algorithms. Mean-field Games (MFGs) are a continuous approximation of
many-agent RL. They consider the limit case of a continuous distribution of identical agents, anonymous
with symmetric interests, and reduce the problem to the study of a single representative agent in interaction
with the full population. Our core contribution consists in showing that CURL is a subclass of MFGs.
We think this important to bridge together both communities. It also allows to shed light on aspects of
both fields: we show the equivalence between concavity in CURL and monotonicity in the associated
MFG, between optimality conditions in CURL and Nash equilibrium in MFG, or that Fictitious Play
(FP) for this class of MFGs is simply Frank-Wolfe, bringing the first convergence rate for discrete-time
FP for MFGs. We also experimentally demonstrate that, using algorithms recently introduced for solving
MFGs, we can address the CURL problem more efficiently."

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

url_pdf: https://arxiv.org/pdf/2106.03787.pdf
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
