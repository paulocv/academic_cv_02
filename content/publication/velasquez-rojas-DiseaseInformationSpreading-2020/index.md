---
# Page metadata
# ================
title: "Disease and Information Spreading at Different Speeds in Multiplex Networks"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: true  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`

- Fátima Velásquez-Rojas

- admin

- Colm Connaughton

- Yamir Moreno

- Francisco A. Rodrigues

- Federico Vazquez

# Example:
# - First Mid Last
# - John Doe

# THIS is the paper publication date!
date: 2020-08-24T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1103/PhysRevE.102.022312"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Physical Review E [Vol 102, (Issue 2)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "Phys Rev E 102 2"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Nowadays, one of the challenges we face when carrying out modeling of epidemic spreading is to develop methods to control disease transmission. In this article we study how the spreading of knowledge of a disease affects the propagation of that disease in a population of interacting individuals. For that, we analyze the interaction between two different processes on multiplex networks: the propagation of an epidemic using the susceptible-infected-susceptible dynamics and the dissemination of information about the disease -- and its prevention methods -- using the unaware-aware-unaware dynamics, so that informed individuals are less likely to be infected. Unlike previous related models where disease and information spread at the same time scale, we introduce here a parameter that controls the relative speed between the propagation of the two processes. We study the behavior of this model using a mean-field approach that gives results in good agreement with Monte Carlo simulations on homogeneous complex networks. We find that increasing the rate of information dissemination reduces the disease prevalence, as one may expect. However, increasing the speed of the information process as compared to that of the epidemic process has the counterintuitive effect of increasing the disease prevalence. This result opens an interesting discussion about the effects of information spreading on disease propagation.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: Analysis of epidemics and information spread on homogeneous networks.  # Will be filled manually.

tags:  # Will be filled manually
- epidemic  # The first tag shows in the featured cards
- monte carlo
- markov chain
- information
- awareness

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://arxiv.org/pdf/2006.01965"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1103/PhysRevE.102.022312"


# Featured image
# =========================
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false  # Set `true` to remove the image from the main publication page.

# Associated Projects (optional).
# ===============================
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
# ================================
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!--- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->