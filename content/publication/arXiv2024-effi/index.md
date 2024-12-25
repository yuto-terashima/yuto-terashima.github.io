---
title: "Efficient computational homogenization via tensor train format"
authors:
- Yuki Sato
- admin
- Ruho Kondo
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-07-26T00:00:00Z" # 実際の発行日を記載
doi: "10.48550/arXiv.2407.18870"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-26T00:00:00Z" # 公開日を記載

# Publication type.
publication_types: ["article-preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "*arXiv preprint*. arXiv.2407.18870"

abstract: |
  Real-world physical systems, like composite materials and porous media, exhibit complex heterogeneities and multiscale nature, posing significant computational challenges. Computational homogenization is useful for predicting macroscopic properties from the microscopic material constitution. It involves defining a representative volume element (RVE), solving governing equations, and evaluating its properties such as conductivity and elasticity. Despite its effectiveness, the approach can be computationally expensive. This study proposes a tensor-train (TT)-based asymptotic homogenization method to address these challenges. By deriving boundary value problems at the microscale and expressing them in the TT format, the proposed method estimates material properties efficiently. We demonstrate its validity and effectiveness through numerical experiments applying the proposed method for homogenization of thermal conductivity and elasticity in two- and three-dimensional materials, offering a promising solution for handling the multiscale nature of heterogeneous systems.

# Summary. An optional shortened abstract.
# summary: |
#   Efficient computational homogenization framework using tensor train format for multi-scale problems.

tags:
- Tensor Train
- Computational Homogenization
- Multi-scale Modeling
featured: true

# Links to external resources.
url_pdf: https://arxiv.org/pdf/2407.18870
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
image:
  caption: 'Illustration of tensor train-based homogenization'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
# projects: []

# Slides (optional).
# slides: ""
---