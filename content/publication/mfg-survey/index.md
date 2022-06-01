---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning Mean Field Games: A Survey
authors: [Mathieu Laurière, Sarah Perrin, Matthieu Geist, Olivier Pietquin]
date: 2022-05-26T16:48:05+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T16:48:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

abstract: "
Non-cooperative and cooperative games with a very large number of players have many applications but remain generally
intractable when the number of players increases. Introduced by Lasry and Lions, and Huang, Caines and Malhamé, Mean 
Field Games (MFGs) rely on a mean-field approximation to allow the number of players to grow to infinity. Traditional 
methods for solving these games generally rely on solving partial or stochastic differential equations with a full 
knowledge of the model. Recently, Reinforcement Learning (RL) has appeared promising to solve complex problems. By 
combining MFGs and RL, we hope to solve games at a very large scale both in terms of population size and environment 
complexity. In this survey, we review the quickly growing recent literature on RL methods to learn Nash equilibria in 
MFGs. We first identify the most common settings (static, stationary, and evolutive). We then present a general 
framework for classical iterative methods (based on best-response computation or policy evaluation) to solve MFGs in an 
exact way. Building on these algorithms and the connection with Markov Decision Processes, we explain how RL can be used 
to learn MFG solutions in a model-free way. Last, we present numerical illustrations on a benchmark problem, and 
conclude with some perspectives."

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

url_pdf: https://arxiv.org/pdf/2205.12944.pdf
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
