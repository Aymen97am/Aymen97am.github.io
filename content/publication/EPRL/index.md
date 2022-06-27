---
title: 'Near Instance-Optimal PAC Reinforcement Learning for Deterministic MDPs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile. (https://people.kth.se/~alepro/)
authors: [Andrea Tirinzoni, admin, Emilie Kaufmann]

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-06-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv preprint*

abstract: In probably approximately correct (PAC) reinforcement learning (RL), an agent is required to identify an $\\epsilon$-optimal policy with probability $1-\\delta$. While minimax optimal algorithms exist for this problem, its instance-dependent complexity remains elusive in episodic Markov decision processes (MDPs). In this paper, we propose the first (nearly) matching upper and lower bounds on the sample complexity of PAC RL in deterministic episodic MDPs with finite state and action spaces. In particular, our bounds feature a new notion of sub-optimality gap for state-action pairs that we call the deterministic return gap. While our instance-dependent lower bound is written as a linear program, our algorithms are very simple and do not require solving such an optimization problem during learning. Their design and analyses employ novel ideas, including graph-theoretical concepts such as minimum flows and maximum cuts, which we believe to shed new light on this problem.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Markov Decision Processes", "PAC RL", "Pure Exploration"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: PDF
   url: https://arxiv.org/pdf/2203.09251.pdf
   weight: 1
 - name: Slides
   url: 'JDS_TALK.pdf'
   weight: 2
 - name: Arxiv
   url: https://arxiv.org/abs/2203.09251
   weight: 3
# - name: Cite
#   url: 'cite.bib'
#   weight: 4

#url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
# url_project: ''
# url_slides: 'KLB_TS_CAP2021.pdf'
url_source: ''
url_video: ''

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

