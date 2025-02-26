---
# Page metadata
# ================
title: "Epidemic Spreading with Awareness and Different Timescales in Multiplex Networks"  # Full title of the paper
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
- Fátima Velásquez-Rojas
- Colm Connaughton
- Federico Vazquez
- Yamir Moreno
- Francisco A. Rodrigues

# Example:
# - First Mid Last
# - John Doe

# THIS is the paper publication date!
date: 2019-09-24T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1103/PhysRevE.100.032313"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Physical Review E [Vol 100, (Issue 3)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: "Phys Rev E 100 3"  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  One of the major issues in theoretical modeling of epidemic spreading is the development of methods to control the transmission of an infectious agent. Human behavior plays a fundamental role in the spreading dynamics and can be used to stop a disease from spreading or to reduce its burden, as individuals aware of the presence of a disease can take measures to reduce their exposure to contagion. In this paper, we propose a mathematical model for the spread of diseases with awareness in complex networks. Unlike previous models, the information is propagated following a generalized Maki-Thompson rumor model. Flexibility on the timescale between information and disease spreading is also included. We verify that the velocity characterizing the diffusion of information awareness greatly influences the disease prevalence. We also show that a reduction in the fraction of unaware individuals does not always imply a decrease of the prevalence, as the relative timescale between disease and awareness spreading plays a crucial role in the systems' dynamics. This result is shown to be independent of the network topology. We finally calculate the epidemic threshold of our model, and show that it does not depend on the relative timescale. Our results provide a new view on how information influence disease spreading and can be used for the development of more efficient methods for disease control.
# Example:
#    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi magna nibh, fringilla nec accumsan sed, venenatis a augue. Donec eget venenatis lorem. Fusce molestie feugiat est quis vestibulum. Suspendisse potenti. Pellentesque fermentum blandit quam at blandit. Fusce ut felis suscipit, feugiat lacus ac, placerat magna. An equation : $y = \frac{-b \pm \sqrt{\Delta}}{2a}$.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: A model for the spread of diseases with awareness in multiplex networks.  # Will be filled manually.

tags:  # Will be filled manually
- multilayer  # The first tag shows in the featured cards
- epidemic
- monte carlo
- markov chain

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://arxiv.org/pdf/1812.01386"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1103/PhysRevE.100.032313"


# Featured image
# =========================
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Schematic represetantion of an epidemic model with awareness.'
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
#slides: example
---

<!--- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->