---
# Page metadata
# ================
title: "Assessing the Effectiveness of Test-Trace-Isolate Interventions Using a Multi-Layered Temporal Network"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: false  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`

- Yunyi Cai
- Weiyi Wang
- Lanlan Yu
- Ruixiao Wang
- Gui-Quan Sun
- Allisandra G. Kummer
- Paulo C. Ventura
- Jiancheng Lv
- Marco Ajelli
- Quan-Hui Liu

# THIS is the paper publication date!
date: 2025-09-01T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1016/j.idm.2025.03.005"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Infectious Disease Modelling [Vol 10, (Issue 3)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "Inf. Dis. Mod. 10(3)"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  In the early stage of an infectious disease outbreak, public health strategies tend to gravitate towards non-pharmaceutical interventions (NPIs) given the time required to develop targeted treatments and vaccines. One of the most common NPIs is Test-Trace-Isolate (TTI). One of the factors determining the effectiveness of TTI is the ability to identify contacts of infected individuals. In this study, we propose a multi-layer temporal contact network to model transmission dynamics and assess the impact of different TTI implementations, using SARS-CoV-2 as a case study. The model was used to evaluate TTI effectiveness both in containing an outbreak and mitigating the impact of an epidemic. We estimated that a TTI strategy based on home isolation and testing of both primary and secondary contacts can contain outbreaks only when the reproduction number is up to 1.3, at which the epidemic prevention potential is 88.2\% (95\% CI: 87.9\%--88.5\%). On the other hand, for higher value of the reproduction number, TTI is estimated to noticeably mitigate disease burden but at high social costs (e.g., over a month in isolation/quarantine per person for reproduction numbers of 1.7 or higher). We estimated that strategies considering quarantine of contacts have a larger epidemic prevention potential than strategies that either avoid tracing contacts or require contacts to be tested before isolation. Combining TTI with other social distancing measures can improve the likelihood of successfully containing an outbreak but the estimated epidemic prevention potential remains lower than 50\% for reproduction numbers higher than 2.1. In conclusion, our model-based evaluation highlights the challenges of relying on TTIs to contain an outbreak of a novel pathogen with characteristics similar to SARS-CoV-2, and that the estimated effectiveness of TTI depends on the way contact patterns are modeled, supporting the relevance of obtaining comprehensive data on human social interactions to improve preparedness.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: Evaluate Test-Trace-Isolate protocols under a modeling approach.  # Will be filled manually.

tags:  # Will be filled manually. These tags create categories in the website.
- NPI  # The first tag shows in the featured cards
- TTI
- Epidemic

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://doi.org/10.1016/j.idm.2025.03.005"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1016/j.idm.2025.03.005"


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