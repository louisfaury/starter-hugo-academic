---
title: "A Technical Note on Non-Stationary Parametric Bandits: Existing Mistakes and Preliminary Solutions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yoan Russac
- Marc Abeille
- Clément Calauzènes

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 32nd International Conference on Algorithmic Learning Theory (*ALT*)
publication_short: In *ALT*

abstract: In this note we identify several mistakes appearing in the existing literature on non-stationary parametric bandits. More precisely, we study Generalized Linear Bandits (GLBs) in drifting environments, where the level of non-stationarity is characterized by a general metric known as the variation-budget. Existing methods to solve such problems typically involve forgetting mechanisms, which allow for a fine balance between the learning and tracking requirements of the problem. We uncover two significant mistakes in their theoretical analysis. The first arises when bounding the tracking error suffered by forgetting mechanisms. The second emerges when considering non-linear reward models, which requires extra care to balance the learning and tracking guarantees. We introduce a geometrical assumption on the arm set, sufficient to overcome the aforementioned technical gaps and recover minimax-optimality. We also share preliminary attempts at fixing those gaps under general configurations. Unfortunately, our solution yields degraded rates (w.r.t to the horizon), which raises new open questions regarding the optimality of forgetting mechanisms in non-stationary parametric bandits.

# Summary. An optional shortened abstract.
summary: ALT 2021.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://proceedings.mlr.press/v132/faury21a/faury21a.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


