---
# Page metadata
# ================
title: "A Markov Chain for Metapopulations of Small Sizes with Attraction Landscape"  # Full title of the paper
draft: false

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: false  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`

- admin
- Eric K. Tokuda
- Luciano da F. Costa
- Francisco A. Rodrigues

# THIS is the paper publication date!
date: 2023-02-01T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1016/j.chaos.2022.113003"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Chaos, Solitons & Fractals [Vol 167]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "Chaos, Sol. & Frac. 167"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Mathematical models represent one of the fundamental ways of studying nature. In special, epidemic models have shown to be particularly useful in the understanding of the course of diseases and in the planning effective control policies. A particular type of epidemic model considers the individuals divided into populations. When studied in graphs, it is already known that the graph topology can play an important role in the evolution of the disease. At the same time, one may want to study the effect of the presence of an underlying attraction landscape of the vertices, apart from the respectively underlying topology. In this work, we study metapopulations with small number of individuals in the presence of an attraction landscape. Individuals move across populations and get infected according to the SIS compartmental model. By using a Markov chain approach, we provide a numerical approximation to the prediction of the long-term prevalence of the disease. More specifically, an approach that combines two binomial distributions for mobility, with appropriate assumptions, is proposed to approximate the model. The problem setting is simulated through Monte-Carlo experiments and the obtained results are compared to the mathematic-analytical approach. Substantial agreement is observed between both approaches, which corroborates the effectiveness of the reported numerical approach. In addition, we also study the impact of different levels of attraction landscapes, as well as propagation on the local scale of the entire population. All in all, this study proposes a potentially effective approach to a mostly unexplored setting of disease transmission.


# An optional shortened abstract, shows up in featured cards of the publication.
summary: Epidemic spread in metapopulations with small number of individuals and a landscape.  # Will be filled manually.

tags:  # Will be filled manually
- Epidemic  # The first tag shows in the featured cards
- Markov chain
- Monte Carlo


# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://arxiv.org/pdf/2111.13168"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1016/j.chaos.2022.113003"


# Featured image
# =========================
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image adapted from <a href="https://pixabay.com/users/clker-free-vector-images-3736/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=311272">Clker-Free-Vector-Images</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=311272">Pixabay</a>'
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
slides: ""
---

<!--- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->