---
# Page metadata
# ================
title: "VIBES: A Multi-Scale Modeling Approach Integrating Within-Host and Between-Hosts Dynamics in Epidemics"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: true  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`

- admin
- Yong Dam Jeong
- Maria Litvinova
- Allisandra G. Kummer
- Shingo Iwami
- Hongjie Yu
- Stefano Merler
- Alessandro Vespignani
- Keisuke Ejima
- Marco Ajelli

# THIS is the paper publication date!
date: 2025-08-19T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.48550/arXiv.2508.13354"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "_arXiv_ [(2508.13354)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "arXiv 2508.13354"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Infectious disease spread is a multi-scale process composed of within-host (biological) and between-host (social) drivers and disentangling them from each other is a central challenge in epidemiology. Here, we introduce VIBES, a multi-scale modeling framework that explicitly integrates viral dynamics based on patient-level data with population-level transmission on a data-driven network of social contacts. Using SARS-CoV-2 as a case study, we analyze three emergent epidemic properties, namely the generation time, serial interval, and pre-symptomatic transmission. First, we established a purely biological baseline, thus independent of the reproduction number (R), from the within-host model, estimating a generation time of 6.3 days for symptomatic individuals and 43.1\% presymptomatic transmission. Then, using the full model incorporating social contacts, we found a shorter generation time (5.4 days at R=3.0) and an increase in pre-symptomatic transmission (52.8\% at R=3.0), disentangling the impact of social drivers from a purely biological baseline. We further show that as pathogen transmissibility increases (R from 1.3 to 6), competition among infectious individuals shortens the generation time and serial interval by up to 21\% and 13\%, respectively. Conversely, a social intervention, like isolation, increases the proportion of pre-symptomatic transmission by about 30\%. Our framework also estimates metrics that are challenging to obtain empirically, such as the generation time for asymptomatic individuals (5.6 days; 95\%CI: 5.1-6.0 at R=1.3). Our findings establish multi-scale modeling as a powerful tool for mechanistically quantifying how pathogen biology and human social behavior shape epidemic dynamics as well as for assessing public health interventions.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: A mechanistic approach to disentangle effects of biological and social processes on epidemic outbreak.  # Will be filled manually.

tags:  # Will be filled manually. These tags create categories in the website.
- Preprint  # The first tag shows in the featured cards
- Generation time
- Epidemic
- COVID-19
- NPI

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://doi.org/10.48550/arXiv.2508.13354"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.48550/arXiv.2508.13354"


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
projects: ["vibes"]

# Slides (optional).
# ================================
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!--- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->