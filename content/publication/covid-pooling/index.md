---
title: 'An study on the suitability of different pooling operators for Convolutional Neural Networks in the prediction of COVID-19 through chest x-ray image analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pablo Ursua-Medrano
  - Javier Fernandez
  - Zdenko Takáč
  - Humberto Bustince

# Author notes (optional)
author_notes:
  - 'Investigation, Methodology, Software, Writing – original draft.'
  - 'Data curation, Formal analysis, Software, Writing – original draft.'
  - 'Supervision, Writing – review & editing.'
  - 'Validation, Writing – review & editing.'
  - 'Project administration, Supervision.'

date: '2023-08-16T00:00:00Z'
doi: 'https://doi.org/10.1016/j.eswa.2023.121162'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Expert Systems with Applications*
publication_short: In *ESWA*

abstract: The 2019 coronavirus disease outbreak, caused by the severe acute respiratory syndrome type-2 virus (SARS-CoV-2), was declared a pandemic in March 2020. Since its emergence to the present day, this disease has brought multiple countries to the brink of health care collapse during several waves of the disease. One of the most common tests performed on patients is chest x-ray imaging. These images show the severity of the patient’s illness and whether it is indeed covid or another type of pneumonia. Automated assessment of this type of imaging could alleviate the time required for physicians to treat and diagnose each patient. To this end, in this paper we propose the use of Convolutional Neural Networks (CNNs) to carry out this process. The aim of this paper is twofold. Firstly, we present a pipeline adapted to this problem, covering all steps from the preprocessing of the datasets to the generation of classification models based on CNNs. Secondly, we have focused our study on the modification of the information fusion processes of this type of architectures, in the pooling layers. We propose a number of aggregation theory functions that are suitable to replace classical processes and have shown their benefits in past applications, and study their performance in the context of the x-ray classification problem. We find that replacing the feature reduction processes of CNNs leads to drastically different behaviours of the final model, which can be benefitial when prioritizing certain metrics such as precision or recall.

# Summary. An optional shortened abstract.
summary: The COVID-19 pandemic since 2019 has strained healthcare globally. In such a context, chest x-ray images are vital for diagnosis. Automating their classification through Convolutional Neural Networks (CNNs) can save time. In this paper we propose a CNN-based pipeline for diagnosis that focuses on improving information fusion in pooling layers with new aggregation functions. Replacing traditional CNN processes yields varied model behaviors, useful for prioritizing metrics like precision or recall.

tags: [Convolutional neural networks, Pooling functions, Aggregation functions, COVID-19, SARS-CoV-2]

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
projects: []
  # - 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
