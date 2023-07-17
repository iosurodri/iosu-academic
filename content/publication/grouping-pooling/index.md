---
title: 'Generalizing max pooling via (a, b)-grouping functions for Convolutional Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tiago Asmus
  - Graçaliz Dimuro
  - Francisco Herrera
  - Zdenko Takáč
  - Humberto Bustince

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-06-21T00:00:00Z'
doi: 'https://doi.org/10.1016/j.inffus.2023.101893'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Information Fusion*
publication_short: In *Inffus*

abstract: Due to their high adaptability to varied settings and effective optimization algorithm, Convolutional Neural Networks (CNNs) have set the state-of-the-art on image processing jobs for the previous decade. CNNs work in a sequential fashion, alternating between extracting significant features from an input image and aggregating these features locally through “pooling” functions, in order to produce a more compact representation. Functions like the arithmetic mean or, more typically, the maximum are commonly used to perform this downsampling operation. Despite the fact that many studies have been devoted to the development of alternative pooling algorithms, in practice, “max-pooling” still equals or exceeds most of these possibilities, and has become the standard for CNN construction. In this paper we focus on the properties that make the maximum such an efficient solution in the context of CNN feature downsampling and propose its replacement by grouping functions, a family of functions that share those desirable properties. In order to adapt these functions to the context of CNNs, we present (a, b)-grouping functions, an extension of grouping functions to work with real valued data. We present different construction methods for (a, b)-grouping functions, and demonstrate their empirical applicability for replacing max-pooling by using them to replace the pooling function of many well-known CNN architectures, finding promising results.

# Summary. An optional shortened abstract.
summary: Despite numerous studies on pooling algorithms, max-pooling remains the standard choice in CNNs. In this work, we introduce (a, b)-grouping functions, an extension of grouping functions tailored for real-valued data in CNNs. We present various construction methods for (a, b)-grouping functions and empirically demonstrate their effectiveness by replacing max-pooling in popular CNN architectures, yielding promising results. Our findings highlight the potential of grouping functions as efficient alternatives to max-pooling in CNN feature downsampling.

tags: [Convolutional neural networks, Grouping functions, Pooling functions, Image classification]

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
  - grouping-pooling

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
