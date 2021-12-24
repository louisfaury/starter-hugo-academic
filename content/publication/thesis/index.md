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
publication: 
publication_short: 

abstract: In this dissertation we present recent contributions to the problem ofoptimization under bandit feedback through the design of variance-sensitive confidence intervals.We tackle two distincts topics: *(1)* the regret minimization task in Generalized Linear Bandits(GLBs for short, a broad class of non-linear parametric bandits) and *(2)* the problem of off-linepolicy optimization under bandit feedback. For *(1)* we study the effects of non-linearity in GLBsand challenge the current understanding that a high level of non-linearity is detrimental to theexploration-exploitation trade-off. We introduce improved algorithms as well as a novel analysisthat prove that if correctly handled the regret minimization task in GLBs is not necessarilyharder than for their linear counterparts. It can even be easier for some important membersof the GLB family such as the Logistic Bandit. Our approach leverages a new confidenceset which captures the non-linearity of the reward signal through its variance, along with alocal treatment of the non-linearity through a so-called self-concordance analysis. For *(2)* weleverage results from the distributionally robust optimization framework to construct asymptoticvariance-sensitive confidence intervals for the counterfactual evaluation of policies. This allowsto ensure conservatism (sought out by risk-averse agents) while searching off-line for promisingpolicies. Our confidence intervals lead to new counterfactual objectives which, contrary to theirpredecessors, are more suited for practical deployment thanks to their convex and compositenatures.

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
