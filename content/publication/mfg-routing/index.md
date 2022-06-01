---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Solving N-player dynamic routing games with congestion: a mean field approach"
authors: [Theophile Cabannes, Mathieu Lauriere, Julien Perolat, Raphael Marinier, Sertan Girgin, Sarah Perrin, 
          Olivier Pietquin, Alexandre M Bayen, Eric Goubault, Romuald Elie]
date: 2021-05-28T16:48:05+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T16:48:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "
The recent emergence of navigational tools has changed traffic patterns and has now enabled new types of 
congestion-aware routing control like dynamic road pricing. Using the fundamental diagram of traffic flows - applied in 
macroscopic and mesoscopic traffic modeling - the article introduces a new N-player dynamic routing game with explicit 
congestion dynamics. The model is well-posed and can reproduce heterogeneous departure times and congestion spill back 
phenomena. However, as Nash equilibrium computations are PPAD-complete, solving the game becomes intractable for large 
but realistic numbers of vehicles N. Therefore, the corresponding mean field game is also introduced. Experiments were 
performed on several classical benchmark networks of the traffic community: the Pigou, Braess, and Sioux Falls networks 
with heterogeneous origin, destination and departure time tuples. The Pigou and the Braess examples reveal that the mean 
field approximation is generally very accurate and computationally efficient as soon as the number of vehicles exceeds a 
few dozen. On the Sioux Falls network (76 links, 100 time steps), this approach enables learning traffic dynamics with 
more than 14,000 vehicles."

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
