---
title: "Variance-Sensitive Confidence Intervals for Parametric and Offline Bandits"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-11"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: PhD Thesis.
publication_short: PhD Thesis.

abstract: Cette thèse présente des contributions récentes au problème d’optimisation sous feedback bandit, au travers de la construction d’intervalles de confiance sensibles à la variance. Nous traitons deux aspects distincts du problème: (1) la minimisation du regret pour les bandits à modèle linéaire généralisé (GLBs), une large classe de bandits paramétriques non-linéaires et (2) le problème d’optimisation de politique hors ligne sous signal bandit. Concernant (1) nous étudions les effets de la non-linéarité dans les GLBs et remettons en question la compréhension actuelle selon laquelle des hauts niveaux de non-linéarité ne peuvent être que préjudiciables à l’équilibre exploration-exploitation. Des algorithmes améliorés suivis d’une nouvelle méthode d’analyse montrent que lorsque correctement manipulé, le problème de minimisation du regret dans les GLBs n’est pas nécessairement plus dur que pour leur contrepartie linéaire. Il peut même être significativement facilité pour certains membres importants de la famille GLB comme le bandit logistique. Notre approche utilise de nouveaux ensembles de confiance sensibles à la non-linéarité au travers de la variance qu’elle impose à la fonction récompense, accompagnés d’un traitement local de la non-linéarité au travers d’une analyse dite auto-concordante. Concernant (2) nous utilisons des résultats de la littérature de l’optimisation robuste afin de construire des intervalles de confiance asymptotiques sensibles à la variance pour l’évaluation contrefactuelle de politiques. Cela permet d’assurer du conservatisme (désirable pour des agents averses au risque) lors de la recherche hors-ligne de politiques prometteuses. Cet intervalle de confiance engendre de nouveaux objectifs contrefactuels qui sont plus adaptés à des applications pratiques, car convexes et de nature composites.

# Summary. An optional shortened abstract.
summary: PhD Thesis.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'final_thesis.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'final_slides.pdf'
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

