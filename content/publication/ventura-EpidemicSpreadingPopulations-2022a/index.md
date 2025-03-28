---
# Page metadata
# ================
title: "Epidemic Spreading in Populations of Mobile Agents with Adaptive Behavioral Response"  # Full title of the paper
draft: false  # ---- SET TO FALSE TO PUBLISH ON PRODUCTION

# Schedule page publish date (NOT the *paper* publication date).
publishDate: "2017-01-01T00:00:00Z"
featured: false  # Set `true` to show on featured publications
# Option to render math between $$.
math: true

# Publication metadata
# ====================
authors:  # Replace yourself with `admin`

- admin
- Alberto Aleta
- Francisco A. Rodrigues
- Yamir Moreno

# THIS is the paper publication date!
date: 2022-02-15T00:00:00Z  # Must be: ISO format. Example: 2019-12-31T00:00:00Z. Time can be midnight. If unavailable, the day can be the first of the month.
doi: "https://doi.org/10.1016/j.chaos.2022.111849"  # Example: "https://doi.org/10.1103/PhysRevE.100.032313"

# Publication: journal name + volume + issue (or page)
publication: "Chaos, Solitons & Fractals [Vol 156, (Issue _No Issue_)]" # Journal and volume. Example: "_Template Journal Name_ [VolN], (IssueN)"   # Shows in the publication page
publication_short: ""  # Shows up in citation format. Will be filled manually later.

# Publication type.
# ==================
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL (Citation Style Language) standard: https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["article-journal"]


# Abstract and Keywords
# =======================
abstract: | 
  Despite the advanced stage of epidemic modeling, there is a major demand for methods to incorporate behavioral responses to the spread of a disease, such as social distancing and adoption of prevention methods. Mobility plays an important role on epidemic dynamics and is also affected by behavioral changes, but there are many situations in which real mobility data is incomplete or inaccessible. We present a model for epidemic spreading in temporal networks of mobile agents that incorporates local behavioral responses. Susceptible agents are allowed to move towards the opposite direction of infected agents in their neighborhood. We show that this mechanism considerably decreases the stationary prevalence when the spatial density of agents is low. However, for higher densities, the mechanism causes an abrupt phase transition, where a new bistable phase appears. We develop a semi-analytic approach for the case when the mobility is fast compared to the disease dynamics, and use it to argue that the bistability is caused by the emergence of spatial clusters of susceptible agents. Finally, we characterize the temporal networks formed in the fast mobility regime, showing how the degree distributions and other metrics are affected by the behavioral mechanism. Our work incorporates results previously known from adaptive networks into population of mobile agents, which can be further developed to be used in mobility-driven models.

# An optional shortened abstract, shows up in featured cards of the publication.
summary: Epidemic spreading among mobile agents that avoid infectious contacts

tags:  # Will be filled manually
- Epidemic
- Agent-based
- Bistability 
- Phase diagram
- Temporal networks

# Publication Links
# ==================
# Add here any material related to the publication.

url_pdf: "https://arxiv.org/pdf/2112.07829"  # Can be manually replaced by an open-access preprint
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:  # Use this to add custom links!
 - name: "Publication"
   url: "https://doi.org/10.1016/j.chaos.2022.111849"


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