---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Generalization in Mean Field Games by Learning Master Policies"
authors: [Sarah Perrin, Mathieu Laurière, Julien Pérolat, Romuald Élie, Matthieu Geist, Olivier Pietquin]
date: 2021-09-28T16:48:05+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T16:48:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AAAI 2022"
publication_short: ""

abstract: "Mean Field Games (MFGs) can potentially scale multi-agent systems to extremely large populations of agents. 
Yet, most of the literature assumes a single initial distribution for the agents, which limits the practical 
applications of MFGs. Machine Learning has the potential to solve a wider diversity of MFG problems thanks to 
generalizations capacities. We study how to leverage these generalization properties to learn policies enabling a 
typical agent to behave optimally against any population distribution. In reference to the Master equation in MFGs, we 
coin the term ``Master policies'' to describe them and we prove that a single Master policy provides a Nash equilibrium, 
whatever the initial distribution. We propose a method to learn such Master policies. Our approach relies on three 
ingredients: adding the current population distribution as part of the observation, approximating Master policies with 
neural networks, and training via Reinforcement Learning and Fictitious Play. We illustrate on numerical examples not 
only the efficiency of the learned Master policy but also its generalization capabilities beyond the distributions used 
for training."

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

url_pdf: https://arxiv.org/pdf/2109.09717.pdf
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
