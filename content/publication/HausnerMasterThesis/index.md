---
title: "Time-Centric Content-Exploration in Large Document Collections"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
author_notes:
- ""

date: "2020-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Master Thesis
publication_short:

abstract: Time is a natural way to order information, and structure the sequence of events, e.g., along a timeline. Such representations allow users to grasp information at-a-glance and can hence replace or at least complement more complicated textual data. The manual construction of timelines, however, can prove to be a tedious and error-prone task. Moreover, such timelines are often static representations of the information given in a data set, and do not allow users to interact with the underlying data, limiting the user to a passive role. Exploratory scenarios aim to give a user an active role, in which she not only absorbs knowledge, but also influences in which ways the information is presented to her. In this thesis, we outline how graph models can be employed to explore document collections in a time-centric fashion, and use temporal information to automatically structure otherwise unstructured textual data. To achieve this, techniques from natural language processing like word co-occurrence extraction and named entity recognition are discussed and employed, focusing particularly on temporal information extraction, which in this thesis is done with the help of the domain-sensitive temporal tagger HeidelTime. Extracted temporal expressions are then used to build a graph model that assigns a term co-occurrence network to each temporal expression present in the document collection, s.t. there is exactly one graph for each point in time mentioned in the data set. Additionally, networks are subclassified depending on the type of time granularity they represent, i.e., if the associated temporal expression is of year, month or day granularity. To account for the varying relevance of a term or entity in regard to a timestamp, a tf-inverse timestamp frequency metric to rank terms for a given set of networks is introduced. Furthermore, we present multiple exploratory scenarios in which the proposed model can be applied, and in this context outline a framework that allows users to explore and gain insights about the chronology of events in a given document collection. To demonstrate the usefulness of the approach, the model is employed to two different data sets, one from a legal and one from a historical domain, and the respective results are discussed, showing that the automatically constructed networks accurately represent information given in the respective data set.

# Summary. An optional shortened abstract.
summary: 
tags: [Text Analytics, Temporal Information, Text Exploration]

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
