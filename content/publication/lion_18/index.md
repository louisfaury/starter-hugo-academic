---
title: "Rover Descent: Learning to Optimize by Learning to Navigate on Prototypical Loss Surfaces"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Flavian Vasile

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2018-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Learning and Intelligent OptimizatioN *(LION)*.
publication_short: In *LION*

abstract: Learning to optimize - the idea that we can learn from data algorithms that optimize a numerical criterion - has recently been at the heart of a growing number of research efforts. One of the most challenging issues within this approach is to learn a policy that is able to optimize over classes of functions that are different from the classes that the policy was trained on. We propose a novel way of framing learning to optimize as a problem of learning a good navigation policy on a partially observable loss surface. To this end, we develop Rover Descent, a solution that allows us to learn a broad optimization policy from training only on a small set of prototypical two-dimensional surfaces that encompasses classically hard cases such as valleys, plateaus, cliffs and saddles and by using strictly zeroth-order information. We show that, without having access to gradient or curvature information, we achieve fast convergence on optimization problems not presented at training time, such as the Rosenbrock function and other two dimensional hard functions. We extend our framework to optimize over high dimensional functions and show good preliminary results.

# Summary. An optional shortened abstract.
summary: LION 2018.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1801.07222.pdf'
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


