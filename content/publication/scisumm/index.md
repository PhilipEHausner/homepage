---
title: "UniHD@CL-SciSumm 2020: Citation Extraction as Search"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Dennis Aumiller
- Satya Almasian
- admin
- Michael Gertz

# Author notes (optional)
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution

date: "2020-11-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the First Workshop on Scholarly Document Processing*
publication_short: In *SDP@EMNLP 2020*

abstract: This work presents the entry by the team from Heidelberg University in the CL-SciSumm 2020 shared task at the Scholarly Document Processing workshop at EMNLP 2020. As in its previous iterations, the task is to highlight relevant parts in a reference paper, depending on a citance text excerpt from a citing paper. We participated in tasks 1A (citation identification) and 1B (citation context classification). Contrary to most previous works, we frame Task 1A as a search relevance problem, and introduce a 2-step re-ranking approach, which consists of a preselection based on BM25 in addition to positional document features, and a top-k re-ranking with BERT. For Task 1B, we follow previous submissions in applying methods that deal well with low resources and imbalanced classes.

# Summary. An optional shortened abstract.
summary: 
tags: [Text Analytics, Machine Learning, Search]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
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
