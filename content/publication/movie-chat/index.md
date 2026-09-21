---
title: 'MovieChat: From Dense Token to Sparse Memory for Long Video Understanding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Enxin Song
  - Wenhao Chai
  - Guanhong Wang
  - Yucheng Zhang
  - Haoyang Zhou
  - Feiyang Wu
  - H. Chi
  - X. Guo
  - T. Ye
  - Y. Zhang
  - Y. Lu
  - J.-N. Hwang
  - Gaoang Wang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-02-27T00:00:00Z'
doi: '10.48550/arXiv.2307.16449'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, pp. 18221–18232
publication_short: In *CVPR 2024*

abstract: Recently, integrating video foundation models and large language models to build a video understanding system can overcome the limitations of specific pre-defined vision tasks. Yet, existing systems can only handle videos with very few frames. For long videos, the computation complexity, memory cost, and long-term temporal connection impose additional challenges. Taking advantage of the AtkinsonShiffrin memory model, with tokens in Transformers being employed as the carriers of memory in combination with our specially designed memory mechanism, we propose the MovieChat to overcome these challenges. MovieChat achieves state-of-the-art performance in long video understanding, along with the released MovieChat-1K benchmark with 1K long video and 14K manual annotations for validation of the effectiveness of our method.

# Summary. An optional shortened abstract.
summary: A memory-based system for long video understanding, released with the MovieChat-1K benchmark. Cited 700+ times as of September 2026.

tags:
  - Computer Vision
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2307.16449'
url_code: 'https://github.com/rese1f/MovieChat'
url_dataset: 'https://huggingface.co/datasets/Enxin/MovieChat-1K_train'
url_poster: ''
url_project: 'https://rese1f.github.io/MovieChat/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/embed/Dx5BQmgK4n8?si=FN9pLyQBN--vJBZA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
