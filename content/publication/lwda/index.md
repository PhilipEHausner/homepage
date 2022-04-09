c---
title: "News Article Extraction Using Graph Embeddings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Michael Gertz

# Author notes (optional)
author_notes:
- ""

date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *LWDA - Learning. Knowledge. Data. Analytics. 2021*
publication_short: In *LWDA 2021*

abstract: Content extraction from web pages is a challenging task due to the heterogeneous nature of the web. In this work, a novel method for the extraction of news articles from arbitrary news article pages is presented that aims to identify the main article content, and removes other elements such as advertisements, navigation elements or comments, that are also commonly present on news article pages. To achieve this, the method utilizes the structure of the DOM tree, which underlies each web page as a hierarchical graph structure, and applies graph representation learning to compute suitable graph embeddings. These graph embeddings are then used to classify web page elements as content or no content, and an additional refinement step then extracts the main article text and removes remaining noise. In the final evaluation on a hand annotated data set collected from 16 German news outlets, we showcase that our method beats all baselines by a significant margin, while only being trained on a comparatively small data set.

# Summary. An optional shortened abstract.
summary: 
tags: [Graph Representation Learning, Web Content Extraction, Boilerplate Removal]

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
