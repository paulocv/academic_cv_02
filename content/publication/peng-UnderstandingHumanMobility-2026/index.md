---
# Page metadata
# ================
title: "Understanding Human Mobility Patterns under a Public Health Emergency"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: false  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`
- Cheng Peng
- Nana Chen
- Bo-Wen Ming
- Anqi Zhang
- Yao Zuo
- admin
- Hongjie Yu
- Marco Ajelli
- Juanjuan Zhang

# Example:
# - First Mid Last
# - John Doe

# THIS is the paper publication date!
date: 2026-03-01T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1016/j.idm.2025.10.009"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Infectious Disease Modelling [Vol 11, (Issue 1)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "Infec Dis Mod 11(1)"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Background: Understanding human mobility changes during epidemics is critical for predicting disease spread and planning interventions. However, capturing fine-scale dynamics is challenging. Methods: This study analyzed high-resolution human mobility patterns in Shanghai, China, during the 2022 SARS-CoV-2 Omicron BA.2 outbreak using large-scale anonymized cellular signaling data. We investigated mobility shifts across five distinct epidemic phases (pre-outbreak, targeted interventions, citywide lockdown, targeted lifting, and reopening) stratified by age, sex, and travel purpose. A comprehensive evaluation of four gravity and four radiation spatial interaction models was conducted to assess their ability to explain the observed mobility patterns under varying demographic and behavioral conditions. Results: Population size and distance were found to be primary drivers of mobility, with notable variations across demographic groups and travel purposes. During the lockdown, mobility significantly decreased, particularly for social-related trips and the working-age population, while the effect of distance was substantially higher. Although mobility volumes recovered post-lockdown, a larger effect of distance persisted, implying long-lasting behavioral changes. Our comparative analysis showed that while several variants of gravity and radiation models captured overall patterns effectively, their performance was context-dependent, varying significantly across epidemic phases, population subgroups, and travel purposes. Conclusion: These findings highlight the importance of integrating different mobility models to capture the complex human mobility picture by different population groups during an epidemic outbreak. Overall, this study advances our understanding of behavioral adaptations during crises, enhancing preparedness and response planning.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: Mobility impacts of the SARS-CoV-2 Omicron outbreak in Shanghai, using gravity/radiation models and cellular data.  # Will be filled manually.

tags:  # Will be filled manually. These tags create categories in the website.
- Mobility  # The first tag shows in the featured cards
- China
- COVID-19
- Gravity model
- Lockdown

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://doi.org/10.1016/j.idm.2025.10.009"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1016/j.idm.2025.10.009"


# Featured image
# =========================
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image by <a href="https://pixabay.com/users/lancier-16507166/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=6569760">Zhu Bing</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=6569760">Pixabay</a>'
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