---
title: 'SMCP3: SMC with Probabilistic Program Proposals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - alexlew
  - admin
  - Tan Zhi-Xuan
  - Matin Ghavamizadeh
  - Nishad Gothoskar
  - Stuart Russell
  - Vikash K. Mansinghka

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-01-01'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: The International Conference on Artificial Intelligence and Statistics, 2023
publication_short: "*AISTATS, 2023*"

abstract: "This paper introduces SMCP3, a method for automatically implementing custom sequential Monte Carlo samplers for inference in probabilistic programs. Unlike particle filters and resample-move SMC (Gilks and Berzuini, 2001), SMCP3 algorithms can improve the quality of samples and weights using pairs of Markov proposal kernels that are also specified by probabilistic programs. Unlike Del Moral et al. (2006b), these proposals can themselves be complex probabilistic computations that generate auxiliary variables, apply deterministic transformations, and lack tractable marginal densities. This paper also contributes an efficient implementation in Gen that eliminates the need to manually derive incremental importance weights. SMCP3 thus simultaneously expands the design space that can be explored by SMC practitioners and reduces the implementation effort. SMCP3 is illustrated using applications to 3D object tracking, state-space modeling, and data clustering, showing that SMCP3 methods can simultaneously improve the quality and reduce the cost of marginal likelihood estimation and posterior inference."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/SMCP3.pdf'
url_code: 'https://github.com/probcomp/GenSMCP3.jl'
url_dataset: ''
url_poster: 'uploads/SMCP3Poster-aistats2023.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=Pn4_7nzGhF8&t=15s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---