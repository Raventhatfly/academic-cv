---
title: "Diffusion and Flow Matching Policy with Torque Modality"
authors:
- Feiyang Wu
date: "2025-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Work in progress"
publication_short: "Work in progress"

abstract: Diffusion Policy has been prevailing in imitation learning. This project incorporates joint torque modality into the raw Diffusion Policy formulation to improve action performance on contact-rich manipulation tasks, evaluated on an ARX robotic-arm teleoperation pipeline covering wiping and flipping tasks.

# Summary. An optional shortened abstract.
summary: Adding joint torque modality to Diffusion Policy for contact-rich manipulation.

tags:
- Imitation Learning
- Diffusion
- Robotics

featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

Built an ARX robotic-arm teleoperation data collection, training and evaluation pipeline to replicate results from Diffusion Policy (DP) and Flow Matching on basic and contact-demanding wiping and flipping tasks, then incorporated joint torque modality into raw DP, observing improved action performance on contact-rich tasks.
