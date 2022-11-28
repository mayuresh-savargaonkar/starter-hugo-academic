---
title: 'Uncorrelated Sparse Autoencoder With Long Short-Term Memory for State-of-Charge Estimations in Lithium-Ion Battery Cells'

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

date: '2022-11-23T00:00:00Z'
doi: '10.1109/TASE.2022.3222759'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Automation Science and Engineering
publication_short:

abstract: For the safe and reliable operation of battery-driven machines, accurate state-of-charge (SOC) estimations are necessary. Unfortunately, existing methods often fail to identify patterns relevant to long-term SOC estimation due to complex battery cell characteristics such as aging. In this paper, we propose the Uncorrelated Sparse Autoencoder with Long Short-Term Memory (USAL). USAL is a novel neural network that addresses the challenging task of long-term SOC estimation given a limited initial history of a cell’s charge-discharge behavior. USAL uses a multi-task learning strategy to harness the advantages of sparse autoencoders and Long Short-term Memory (LSTM) networks by enforcing correlation penalties. The USAL simultaneously learns to (i) generate a latent space of informative SOC encodings from commonly measured cell characteristics, (ii) penalize for high multicollinearity between encodings, and (iii) identify non-trivial long and short temporal correlations between the encodings using LSTM cells. USAL outperforms benchmarked models in our experiments when trained on five initial charge-discharge cycles across multiple battery cells using three publicly available accelerated aging datasets. Note to Practitioners —This paper proposes USAL, a custom-built deep neural network to address the challenging task of long-term SOC estimations in battery cells. Long-term SOC estimation involves estimating SOC for cycles near End-Of-Life (EOL) given some initial charge-discharge cycles. Three fundamental steps involved in long-term SOC estimations using USAL are (i) exploiting a multi-task learning strategy to learn efficient encodings given limited training data, (ii) penalizing these encodings for high correlations to efficiently transform measured inputs into a space of informative features, and (iii) mapping of aging-related trends to support long-term SOC estimations. USAL is designed to be a data-driven SOC estimation method that is (i) capable of alerting the user to a faulty cell when integrated into a real-life Battery Management System (BMS) and (ii) identifying the relative quality of a battery cell from only a few initial charge-discharge cycles.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis # placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9959882'
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
  caption: 'USAL: Uncorrelated Sparse Autoencoder with Long Short-Term Memory'
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
