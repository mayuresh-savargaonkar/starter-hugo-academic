---
title: 'RMOPP: Robust Multi-Objective Post-Processing for Effective Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
# - Robert Ford

# Author notes (optional)
author_notes:
  - 'Primary author'

date: '2021-02-09T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2102.04582'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ArXiV
publication_short:

abstract: Over the last few decades, many architectures have been developed that harness the power of neural networks to detect objects in near real-time. Training such systems requires substantial time across multiple GPUs and massive labeled training datasets. Although the goal of these systems is generalizability, they are often impractical in real-life applications due to flexibility, robustness, or speed issues. This paper proposes RMOPP- A robust multi-objective post-processing algorithm to boost the performance of fast pre-trained object detectors with a negligible impact on their speed. Specifically, RMOPP is a statistically driven, post-processing algorithm that allows for simultaneous optimization of precision and recall. A unique feature of RMOPP is the Pareto frontier that identifies dominant possible post-processed detectors to optimize for both precision and recall. RMOPP explores the full potential of a pre-trained object detector and is deployable for near real-time predictions. We also provide a compelling test case on YOLOv2 using the MS-COCO dataset.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis # placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2102.04582'
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
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---
