---
title: 'Optimistic PAC Reinforcement Learning: the Instance-Dependent View'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile. (https://people.kth.se/~alepro/)
authors: [Andrea Tirinzoni, admin, Emilie Kaufmann]

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-02-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Algorithmic Learning Theory 2023*
publication_short: In *ALT 2023*

abstract: Optimistic algorithms have been extensively studied for regret minimization in episodic tabular Markov Decision Processes (MDPs), both from a minimax and an instance-dependent view. However, for the PAC RL problem, where the goal is to identify a near-optimal policy with high probability, little is known about their instance-dependent sample complexity. A negative result of Wagenmaker et al.(2022) suggests that optimistic sampling rules cannot be used to attain the (still elusive) optimal instance-dependent sample complexity. On the positive side, we provide the first instance-dependent bound for an optimistic algorithm for PAC RL, BPI-UCRL, for which only minimax guarantees were available (Kaufmann et al., 2021). While our bound features some minimal visitation probabilities, it also features a refined notion of sub-optimality gap compared to the value gaps that appear in prior work. Moreover, in MDPs with deterministic transitions, we show that BPI-UCRL is actually near instance-optimal (up to a factor of the horizon). On the technical side, our analysis is very simple thanks to a new “target trick” of independent interest. We complement these findings with a novel hardness result explaining why the instance-dependent complexity of PAC RL cannot be easily related to that of regret minimization, unlike in the minimax regime.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Markov Decision Processes", "PAC RL", "Optimistic Algorithms"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: PDF
   url: https://proceedings.mlr.press/v201/tirinzoni23a/tirinzoni23a.pdf
   weight: 1
#  - name: Slides
#    url: 'JDS_TALK.pdf'
#    weight: 2
 - name: Arxiv
   url: https://arxiv.org/abs/2207.05852
   weight: 2
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

