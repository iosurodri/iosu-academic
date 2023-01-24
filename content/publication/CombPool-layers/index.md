---
title: 'Replacing pooling functions in Convolutional Neural Networks by linear combinations of increasing functions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Julio Lafuente
  - Santiago Regivan
  - Graçaliz Dimuro
  - Francisco Herrero
  - Humberto Bustince

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-01-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neural Networks*
publication_short: In *Neural Netw.*

abstract: Traditionally, Convolutional Neural Networks make use of the maximum or arithmetic mean in order to reduce the features extracted by convolutional layers in a downsampling process known as pooling. However, there is no strong argument to settle upon one of the two functions and, in practice, this selection turns to be problem dependent. Further, both of these options ignore possible dependencies among the data. We believe that a combination of both of these functions, as well as of additional ones which may retain different information, can benefit the feature extraction process. In this work, we replace traditional pooling by several alternative functions. In particular, we consider linear combinations of order statistics and generalizations of the Sugeno integral, extending the latter’s domain to the whole real line and setting the theoretical base for their application. We present an alternative pooling layer based on this strategy which we name “CombPool” layer. We replace the pooling layers of three different architectures of increasing complexity by CombPool layers, and empirically prove over multiple datasets that linear combinations outperform traditional pooling functions in most cases. Further, combinations with either the Sugeno integral or one of its generalizations usually yield the best results, proving a strong candidate to apply in most architectures.

# Summary. An optional shortened abstract.
summary: ""

tags: [Information Fusion, Convolutional Neural Networks]

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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - CombPool-layers

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
