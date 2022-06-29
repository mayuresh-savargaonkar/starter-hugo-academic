---
title: 'Conditional Gaussian Mixture Model for Warranty Claims Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
# - Robert Ford

# Author notes (optional)
author_notes:
  - 'Primary author'

date: '2022-02-01T00:00:00Z'
doi: ' https://doi.org/10.1016/j.ress.2021.108180'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Reliability Engineering & System Safety
publication_short: RESS

abstract: Forecasting warranty claims for complex products is a reliability challenge for most manufacturers. Several factors increase the complexity of warranty claims forecasting, including, the limited number of claims reported at the early stage of launch, reporting delays, dynamic change in the fleet size, and design/manufacturing adjustments for the production line. The aggregated effect of those complexities is often referred to as the “warranty data maturation” effect. Unfortunately, most of the existing models for warranty claims forecasting fail to explicitly consider warranty data maturation. This work address warranty data maturation by proposing the Conditional Gaussian Mixture Model (CGMM). CGMM uses historical warranty data from similar products to develop a robust prior joint Gaussian mixture distribution of warranty trends at both, the current and future maturation levels. CGMM then utilizes Bayesian theories to estimate the conditional posterior distribution of the warranty claims at the future maturation level conditional on the warranty data available at the current maturation level. The CGMM identifies non-parametric temporal warranty trends and automatically clusters products into latent groups to establish (learn) an effective prior joint distribution. The CGMM is validated on an extensive automotive warranty claims dataset comprising of four model years and >15,000 different components from >10 million vehicles.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis # placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0951832021006645'
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
  caption: 'Image credit: Elsevier - RESS'
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

# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata # into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
