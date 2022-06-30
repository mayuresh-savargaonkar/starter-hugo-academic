---
title: 'A Novel Neural Network with Gaussian Process Feedback for Modeling the State-of-Charge of Battery Cells'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Abdallah Chehade
  - Ala A. Hussein

# Author notes (optional)
author_notes:
  - 'Primary author'

date: '2022-04-27T00:00:00Z'
doi: ' 10.1109/TIA.2022.3170842'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Industry Applications
publication_short:

abstract: Although several state-of-charge (SOC) estimation methods have been proposed at the battery cell level, limited work has been done to identify the effect of cell aging on SOC estimations. To address this challenge, this paper proposes a novel method for estimating the SOC of Lithium-ion (Li-ion) battery cells by accurately modeling the cell aging and degradation information. The proposed method, termed as NNGP, is a deep neural network with Gaussian process feedback. The novel Gaussian process feedback helps the NNGP correlate SOC trends over consecutive charge-discharge cycles. Instead of time, the NNGP leverages available energy to correlate these SOC trends. The deep neural network within the NNGP then utilizes this information and other measured inputs to capture long-term cell aging and degradation trends. The NNGP leverages the most recent cell information to adapt its weights and estimate the SOC by employing an adaptive weighted training strategy. In our experiments on four Li-ion battery cells from three publicly available accelerated aging datasets, the NNGP clearly outperforms other benchmarked methods. The NNGP is also shown to be a useful prognostic tool capable of accurately estimating the SOC for up to 25 cycles in the future with an MAE below 3.5%. When tested under dynamic driving conditions and unknown initial SOC, the NNGP is shown to offer considerable improvements over other benchmarked state-of-art methods. The derivation of the model followed by experimental evaluation is presented.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis # placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9764385'
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
  caption: 'Image credit: IEEE Transactions on Industry Applications'
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
