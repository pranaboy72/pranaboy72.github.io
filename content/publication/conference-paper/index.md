---
title: 'Denoising Heat-inspired Diffusion with Insulators for Collision Free Motion Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hyunwoo Ryu
  - Jiwoo Kim
  - Soochul Yoo
  - Jongeun Choi
  - Joohwan Seo
  - Nikhil Prakash
  - Roberto Horowitz

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-10-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neurips 2023 Workshop on Diffusion Models*
publication_short: ""

abstract: Diffusion models have risen as a powerful tool in robotics due to their flexibility and multi-modality. While some of these methods effectively address complex problems, they often depend heavily on inference-time obstacle detection and require additional equipment. Addressing these challenges, we present a method that, during inference time, simultaneously generates only reachable goals and plans motions that avoid obstacles, all from a single visual input. Central to our approach is the novel use of a collision-avoiding diffusion kernel for training. Through evaluations against behavior-cloning and classical diffusion models, our framework has proven its robustness. It is particularly effective in multi-modal environments, navigating toward goals and avoiding unreachable ones blocked by obstacles, while ensuring collision avoidance.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://sites.google.com/view/denoising-heat-inspired?usp=sharing

url_pdf: 'conference-paper.pdf'
url_code: 'https://github.com/pranaboy72/denoisingheat'
url_poster: 'https://neurips.cc/virtual/2023/74866'

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
slides: ""
---
