---
title: 'Transforming Worlds: Automated Involutive MCMC for Open Universe Probabilistic Programs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - alexlew
  - Matin Ghavamizadeh
  - Stuart Russell
  - Marco Cusumano-Towner
  - Vikash K. Mansinghka

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-12-31'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

publication: In *Advanced in Approximate Bayesian Inference 2020*
publication_short: In *AABI'20*

abstract: "Open-universe probabilistic models enable Bayesian inference about how many objects underlie data, and how they are related. Effective inference in OUPMs remains a challenge, however, often requiring the use of custom, trans-dimensional MCMC kernels, based on heuristics, deep learning, or domain knowledge, that can be difficult to derive and to implement correctly. This paper adapts the recently introduced involutive MCMC framework to the open-universe setting, and shows how error-prone aspects of kernel design and implementation (e.g., the computation of valid accept/reject probabilities) can be automated, using techniques from probabilistic and differentiable programming. The result is an intuitive design space for MCMC kernels for OUPMs: users write programs that propose incremental changes to possible worlds, creating, deleting, or modifying objects according to arbitrary application-specific logic, and their proposals are automatically converted into stationary MCMC kernels. We demonstrate in preliminary experiments that data-driven involutive MCMC kernels outperform generic probabilistic programming language inference, as well as generic birth/death reversible-jump kernels without application-specific logic."

# Summary. An optional shortened abstract.
summary: "Inference in open-universe probabilistic models can be challenging.  We show how to automate a broad class of MCMC kernels for them, facilitating the development of domain-specific algorithms for inference about unknown objects & their relationships."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=8Itm8dQnJRc'
url_code: 'https://github.com/georgematheos/GenWorldModels.jl'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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