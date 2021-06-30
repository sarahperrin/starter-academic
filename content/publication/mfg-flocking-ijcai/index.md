---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Mean Field Games Flock! The Reinforcement Learning Way"
authors: [Sarah Perrin, Mathieu Laurière, Julien Pérolat, Matthieu Geist, Romuald Élie, Olivier Pietquin]
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
publication: "IJCAI 2021"
publication_short: ""

abstract: "We present a method enabling a large number of agents to learn how to flock, which is a natural behavior 
observed in large populations of animals.
This problem has drawn a lot of interest but requires many structural assumptions and is tractable
only in small dimensions. We phrase this problem
as a Mean Field Game (MFG), where each individual chooses its acceleration depending on the population behavior. Combining Deep Reinforcement
Learning (RL) and Normalizing Flows (NF), we
obtain a tractable solution requiring only very weak
assumptions. Our algorithm finds a Nash Equilibrium and the agents adapt their velocity to match
the neighboring flock’s average one. We use Fictitious Play and alternate: (1) computing an approximate best response with Deep RL, and (2) estimating the next population distribution with NF. We
show numerically that our algorithm learn multigroup or high-dimensional flocking with obstacles."

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

url_pdf: https://arxiv.org/pdf/2105.07933.pdf
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
