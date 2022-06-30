---
title: 'A Hybrid Long Short-Term Memory Network for State-of-Charge Estimation of Li-ion Batteries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Isaiah Oyewole
  - Abdallah Chehade
  - Ala A. Hussein

# Author notes (optional)
author_notes:
  - 'Primary author'

date: '2021-08-02T00:00:00Z'
doi: ' https://doi.org/10.1109/ITEC51675.2021.9490070'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  2021 IEEE Transportation Electrification Conference & Expo (ITEC)
publication_short:

abstract: This paper proposes the Sparse Autoencoded Long Short-Term Memory network (SAEL) for long-term State-of-Charge (SOC) estimations. SAEL addresses the challenge of estimating the SOC near the end-of-life after only running a few charge-discharge cycles. SAEL transforms the inputs (e.g., voltage) into a space of informative features for SOC estimations. SAEL then feeds the transformed features into an LSTM network to identify temporal trends that support long-term SOC estimation. In our experiments, SAEL outperformed benchmark models by over 63% when evaluated on three battery cells. SAEL showed an MAE of 2.6% for the last twenty cycles when trained only on the initial five charge-discharge cycles.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis # placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9490070'
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
