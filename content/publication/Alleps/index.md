---
title: 'On the complexity of All ε-Best Arms Identification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile. (https://people.kth.se/~alepro/)
authors: [admin, Tomáš Kocák, Aurélien Garivier]

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-02-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases 2022*
publication_short: In *ECMLPKDD 2022*

abstract: We consider the question introduced by \\cite{Mason2020} of identifying all the $\varepsilon$-optimal arms in a finite stochastic multi-armed bandit with Gaussian rewards. We give two lower bounds on the sample complexity of any algorithm solving the problem with a confidence at least $1-\\delta$. The first, unimprovable in the asymptotic regime, motivates the design of a Track-and-Stop strategy whose average sample complexity is asymptotically optimal when the risk $\delta$ goes to zero. Notably, we provide an efficient numerical method to solve the convex max-min program that appears in the lower bound. Our method is based on a complete characterization of the alternative bandit instances that the optimal sampling strategy needs to rule out, thus making our bound tighter than the one provided by \\cite{Mason2020}. The second lower bound deals with the regime of high and moderate values of the risk $\delta$, and characterizes the behavior of any algorithm in the initial phase. It emphasizes the linear dependency of the sample complexity in the number of arms. Finally, we report on numerical simulations demonstrating our algorithm's advantage over state-of-the-art methods, even for moderate risks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Multi-armed bandits", "Pure Exploration", "moderate confidence regime"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: PDF
   url: https://arxiv.org/pdf/2202.06280.pdf
   weight: 1
# - name: Slides
#   url: 'KLB_TS_CAP2021.pdf'
#   weight: 2
 - name: Arxiv
   url: https://arxiv.org/abs/2202.06280
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

