---
# Page metadata
# ================
title: "Evaluating Field Trial Designs for Genetically Modified Mosquito Interventions: An In-Silico Simulation Approach"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: false  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`
- Jagadeesh Chitturi
- admin
- Allisandra G. Kummer
- Chalmers Vasquez
- Ethan SeRine
- Megan D. Hill
- Mattia Manica
- Piero Poletti
- John C. Beier
- Keisuke Ejima
- Michael Johansson
- Stefano Merler
- Hongjie Yu
- John-Paul Mutebi
- Maria Litvinova
- André B. B. Wilke
- Marco Ajelli

# Example:
# - First Mid Last
# - John Doe

# THIS is the paper publication date!
date: 2025-11-01T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1101/2025.11.05.686816"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "bioRxiv" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "bioRxiv"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Mosquito control strategies based on the mass release of modified males, such as genetically modified mosquitoes (GMMs), aim to suppress wild populations by impairing reproduction. Evaluating these interventions requires resource-intensive field trials, but a lack of standardized implementation practices, particularly regarding release ratios of modified males to wild female mosquitoes and trial timing, has led to variable outcomes. This study's objective is to propose a modeling tool for the \"in-silico\" simulation of trial designs before field implementation. To this aim, we developed an agent-based model of mosquito population dynamics. As a case study, we calibrated the model using 2019-2023 Aedes aegypti surveillance data from Miami-Dade County, Florida, and compared two GMM trial designs: a \"constant-release\" design (fixed releases based on a baseline entomological survey) and an \"adaptive-release\" design (releases adjusted weekly to the population of the control arm). Our results show that the constant-release design's effectiveness is highly dependent on the trial's start date relative to mosquito seasonality, creating large outcome uncertainty. For a 6-month trial with a 4:1 GMM:wild ratio and constant-release, the median effectiveness across all start dates was 71.4\%, with an interquartile range (IQR) spanning from 55.3\% to 90.0\%. In contrast, the adaptive-release design yielded similar median effectiveness but with a narrower IQR regardless of the start date, trial duration, and release ratio. Overall, effectiveness is closely linked to the total number of mosquitoes released but also dependent on the timing, frequency of releases, release ratio, mosquito fitness, and duration of interventions. Our findings suggest that \"in-silico\" simulation is a valuable tool for improving trial protocol design, allowing stakeholders to test strategies and reduce outcome uncertainty before committing to a fieldwork experiment.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: Simulation of GM mosquito field trials with an agent-based model.  # Will be filled manually.

tags:  # Will be filled manually. These tags create categories in the website.
- preprint  # The first tag shows in the featured cards
- Mosquito
- Aedes aegypti
- Agent-based
- Miami
- In-silico

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://doi.org/10.1101/2025.11.05.686816"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1101/2025.11.05.686816"


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