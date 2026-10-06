---
title: 'Robot Learning with Visual Predicted Force'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haonan Chen
  - Feiyang Wu
  - Yuxiang Ma
  - Mustafa Mete
  - Pengfei Ye
  - Junxuan Shen
  - Cheng Zhu
  - Aurora Ruggeri
  - Kelvin Cheung
  - Jiayuan Mao
  - Edward Adelson
  - Jiajun Wu
  - Robert D. Howe
  - Yilun Du

# Author notes (optional)
author_notes:
  - 'Co-first author'
  - 'Co-first author'

date: '2026-10-03T00:00:00Z'
doi: '10.48550/arXiv.2610.04741'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-10-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: Under review, *ICRA 2027*
publication_short: Under review, *ICRA 2027*

abstract: 'Force-aware manipulation typically relies on specialized force or tactile sensors. We show that force-aware manipulation can instead be achieved through visual force prediction from the deformation of a compliant Fin Ray gripper. Our approach trains two models. First, we train a visual force estimator on calibration data and use it to annotate task demonstrations with force estimates. Second, we train an action--force proposal policy on these force-augmented demonstrations to jointly generate candidate robot actions and their associated forces. At test time, we sample candidate actions and the forces they are expected to produce, then execute the action whose predicted force is closest to a target from the demonstrations. We evaluate our approach on berry picking, empty-can grasping, in-hand reorientation, and plug insertion. Our results show that visual force prediction can guide inference-time action selection for contact-rich manipulation without requiring force or tactile sensors at deployment.'

# Summary. An optional shortened abstract.
summary: Force-aware manipulation without force or tactile sensors, using force predicted visually from a compliant Fin Ray gripper to guide action selection.

tags:
  - Robotics
  - Imitation Learning

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2610.04741'
url_code: 'https://github.com/visual-force/visual-force'
url_dataset: ''
url_poster: ''
url_project: 'https://visual-force.github.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Contact-rich insertion guided by visually predicted force.'
  focal_point: 'Center'
  preview_only: false

projects: []
slides: ''
---
