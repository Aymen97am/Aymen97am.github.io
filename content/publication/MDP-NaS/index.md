---
title: 'Navigating to the Best Policy in Markov Decision Processes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile. (https://people.kth.se/~alepro/)
authors: [admin, Aurélien Garivier, Alexandre Proutiere]

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-05-30'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2021*
publication_short: In *NeurIPS 2021*

abstract: We investigate the classical active pure exploration problem in Markov Decision Processes, where the agent sequentially selects actions and, from the resulting system trajectory, aims at identifying the best policy as fast as possible. We propose a problem-dependent lower bound on the average number of steps required before a correct answer can be given with probability at least $1-\\delta$. We further provide the first algorithm with an instance-specific sample complexity in this setting. This algorithm addresses the general case of communicating MDPs; we also propose a variant with a reduced exploration rate (and hence faster convergence) under an additional ergodicity assumption. This work extends previous results relative to the \\emph{generative setting}~\\cite{pmlr-v139-marjani21a}, where the agent could at each step query the random outcome of any (state, action) pair. In contrast, we show here how to deal with the \emph{navigation constraints}, induced by the \\emph{online setting}. Our analysis relies on an ergodic theorem for non-homogeneous Markov chains which we consider of wide interest in the analysis of Markov Decision Processes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Markov Decision Processes", "Pure Exploration", "Navigation Constraints"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: PDF
   url: https://proceedings.neurips.cc/paper/2021/file/d9896106ca98d3d05b8cbdf4fd8b13a1-Paper.pdf
   weight: 1
 - name: Slides
   url: 'NeurIPS_TALK.pdf'
   weight: 2
 - name: Video
   url: 'https://neurips.cc/virtual/2021/poster/26862'
   weight: 3
 - name: Arxiv
   url: https://arxiv.org/abs/2106.02847
   weight: 4


#url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: ''
# url_slides: 'KLB_TS_CAP2021.pdf'
url_source: ''
# url_video: 'https://neurips.cc/virtual/2021/poster/26862'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:  
---

