---
title: 'CoStream: Composing Simple Behaviors for Generalizable Complex Manipulation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haonan Chen
  - Yuxiang Ma
  - Stephen Tian
  - Xiaoshen Han
  - Wenlong Huang
  - Feiyang Wu
  - Yunzhu Li
  - Jiajun Wu
  - Edward H. Adelson
  - Yilun Du

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: 'Preprint, arXiv:2606.26423 [cs.RO]'
publication_short: 'arXiv:2606.26423'

abstract: "Long-horizon, contact-rich manipulation — such as seating a GPU into a PCIe slot — demands both millimeter precision and generalization to new tasks. Classical pipelines achieve precise control through brittle, task-specific interfaces that need costly redesigns, while monolithic policies generalize better but lose precision on out-of-distribution tasks unless retrained. Both assume a capability, once acquired, must ship as a rigid whole rather than being freely decomposed and recomposed. We show that complex manipulation can emerge from composing simple, independent behaviors. CoStream orchestrates foundation models and diverse sensors into composable core behaviors: a semantic behavior extracting spatial constraints, a predictive behavior forecasting trajectories from imagined videos, and a reactive behavior providing high-frequency tactile corrections. On a shared SE(3) interface, these compose by right-multiplication into one pose command per control step. We demonstrate CoStream on 8 real-world tasks spanning everyday manipulation and precision assembly — with the strongest gains in contact-rich assembly and object transfer — and show robust recovery from manual perturbations during execution."

# Summary. An optional shortened abstract.
summary: Composing semantic, predictive and reactive behaviors on a shared SE(3) interface, so that long-horizon precision manipulation emerges without per-task retraining.

tags:
  - Robotics
  - Imitation Learning
  - Large Language Models

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2606.26423'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://costream-simple.github.io/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'CoStream composes semantic, predictive and reactive behaviors, in contrast to pipelined and end-to-end systems.'
  focal_point: 'Right'
  preview_only: false

projects: []
slides: ''
---

Long-horizon, contact-rich manipulation demands both millimeter precision and generalization to new tasks — requirements that classical task-specific pipelines and monolithic end-to-end policies each satisfy only one half of. CoStream instead treats a capability as something that can be decomposed and recomposed.

## Composable behaviors

CoStream orchestrates foundation models and diverse sensors into three independent core behaviors that share a common SE(3) interface and combine by right-multiplication into a single pose command per control step:

- **Semantic behavior** — extracts spatial constraints for the task.
- **Predictive behavior** — forecasts trajectories from imagined videos.
- **Reactive behavior** — supplies high-frequency tactile corrections.

## Results

Evaluated on 8 real-world tasks spanning everyday manipulation and precision assembly:

- **96.7%** mean success on contact-rich assembly, where the baselines score 0%.
- **66.7%** mean success on everyday manipulation, against 11.7% for π0.5.
- Drill insertion reaches **100%** success with the reactive behavior, dropping to 20% without it.
- Completes a full motherboard assembly (CPU, GPU, RAM) with **zero retraining** between subtasks, and recovers robustly from manual perturbations during execution.

Work done with collaborators at Harvard University, Stanford University, MIT and Columbia University.
