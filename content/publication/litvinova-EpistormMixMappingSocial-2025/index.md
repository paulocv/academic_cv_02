---
# Page metadata
# ================
title: "Epistorm-Mix: Mapping Social Contact Patterns for Respiratory Pathogen Spread in the Post-Pandemic United States"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: true  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`
- Maria Litvinova
- Shelly Sinclair
- Allisandra G. Kummer
- admin
- Trevor Foster
- Kayoko Shioda
- M. Elizabeth Halloran
- Alessandro Vespignani
- Marco Ajelli

# Example:
# - First Mid Last
# - John Doe

# THIS is the paper publication date!
date: 2025-11-21T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1101/2025.11.20.25340662"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "medRxiv" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "medRxiv"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Human contact patterns are a fundamental determinant of respiratory pathogen transmission, yet nationally representative post-pandemic data for the United States are limited. We present Epistorm-Mix, a 2024 probability-based online survey designed to be nationally representative by age, sex, race/ethnicity, household income, census region, and language. Respondents reported all person-to-person contacts from the preceding day, including the contact's age and the setting (household, school, workplace, or community). We quantified contact numbers across demographic and social characteristics and used generalized additive models to test adjusted differences. We constructed age-stratified contact matrices and their setting-specific counterparts, benchmarking them against widely used synthetic matrices to simulate the spread of an epidemic of a respiratory pathogen. We found an average of 7.4 contacts per day, with significant heterogeneity across the population. Contact rates were highest among teenagers (15-19 years) and lowest among older adults (60+ years). In-person attendance at school or work was a major driver, resulting in 2-3 times more contacts than remote participation. We also identified key socioeconomic and demographic group heterogeneities: the number of contacts generally increased with household income, and Non-Hispanic (NH) Black and NH Asian individuals reported statistically significant fewer total contacts than NH White individuals. We found strong assortative mixing by age and demographic group with markedly distinct contact patterns across different social settings (households, schools, workplaces, and the community). While the study's age-mixing patterns are broadly comparable to international findings, the identified demographic heterogeneities reflect social structures unique to the US, underscoring the need for country-specific data. Epistorm-Mix provides a nationally representative portrait of post-pandemic US contact patterns and serves as an open-access resource for modeling and public health planning. Human contact patterns are a fundamental determinant of respiratory pathogen transmission, yet nationally representative post-pandemic data for the United States are limited. We present Epistorm-Mix, a 2024 probability-based online survey designed to be nationally representative by age, sex, race/ethnicity, household income, census region, and language. Respondents reported all person-to-person contacts from the preceding day, including the contact's age and the setting (household, school, workplace, or community). We quantified contact numbers across demographic and social characteristics and used generalized additive models to test adjusted differences. We constructed age-stratified contact matrices and their setting-specific counterparts, benchmarking them against widely used synthetic matrices to simulate the spread of an epidemic of a respiratory pathogen. We found an average of 7.4 contacts per day, with significant heterogeneity across the population. Contact rates were highest among teenagers (15-19 years) and lowest among older adults (60+ years). In-person attendance at school or work was a major driver, resulting in 2-3 times more contacts than remote participation. We also identified key socioeconomic and demographic group heterogeneities: the number of contacts generally increased with household income, and Non-Hispanic (NH) Black and NH Asian individuals reported statistically significant fewer total contacts than NH White individuals. We found strong assortative mixing by age and demographic group with markedly distinct contact patterns across different social settings (households, schools, workplaces, and the community). While the study's age-mixing patterns are broadly comparable to international findings, the identified demographic heterogeneities reflect social structures unique to the US, underscoring the need for country-specific data. Epistorm-Mix provides a nationally representative portrait of post-pandemic US contact patterns and serves as an open-access resource for modeling and public health planning.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: A US-representative 2024 survey on how Americans interact for application in modeling respiratory disease spread. 

tags:  # Will be filled manually. These tags create categories in the website.
- preprint  # The first tag shows in the featured cards
- Survey
- Compartmental
- Contacts
- Contact matrix

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://doi.org/10.1101/2025.11.20.25340662"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1101/2025.11.20.25340662"


# Featured image
# =========================
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image by <a href="https://pixabay.com/users/serpae-12805249/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=5666538">Serp Pae</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=5666538">Pixabay</a>'
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