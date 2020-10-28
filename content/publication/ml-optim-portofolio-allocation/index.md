---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Machine learning optimization algorithms & portfolio allocation"
authors: [Sarah Perrin, Thierry Roncalli]
date: 2019-06-28T17:09:18+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-28T17:09:18+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["5"]

# Publication name and optional abbreviated publication name.
publication: "Machine Learning for Asset Management: New Developments and Financial Applications"
publication_short: ""

abstract: "Portfolio optimization emerged with the seminal paper of Markowitz (1952). The
original mean-variance framework is appealing because it is very efficient from a computational point of view. However, it also has one well-established failing since it can
lead to portfolios that are not optimal from a financial point of view (Michaud, 1989).
Nevertheless, very few models have succeeded in providing a real alternative solution
to the Markowitz model. The main reason lies in the fact that most academic portfolio
optimization models are intractable in real life although they present solid theoretical
properties. By intractable we mean that they can be implemented for an investment
universe with a small number of assets using a lot of computational resources and skills,
but they are unable to manage a universe with dozens or hundreds of assets. However,
the emergence and the rapid development of robo-advisors means that we need to rethink portfolio optimization and go beyond the traditional mean-variance optimization
approach.
Another industry and branch of science has faced similar issues concerning largescale optimization problems. Machine learning and applied statistics have long been
associated with linear and logistic regression models. Again, the reason was the inability
of optimization algorithms to solve high-dimensional industrial problems. Nevertheless,
the end of the 1990s marked an important turning point with the development and the
rediscovery of several methods that have since produced impressive results. The goal of
this paper is to show how portfolio allocation can benefit from the development of these
large-scale optimization algorithms. Not all of these algorithms are useful in our case,
but four of them are essential when solving complex portfolio optimization problems.
These four algorithms are the coordinate descent, the alternating direction method of
multipliers, the proximal gradient method and the Dykstra’s algorithm. This paper
reviews them and shows how they can be implemented in portfolio allocation."

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

url_pdf: https://arxiv.org/pdf/1909.10233.pdf
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
