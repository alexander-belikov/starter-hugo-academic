---
title: "Domain Knowledge Aids in Signal Disaggregation; the Example of the Cumulative Water Heater"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Guillaume Matheron
- Johan Sassi

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# -  "Equal contribution"

date: "2022-03-22T00:00:00Z"
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In *Energy and Buildings*"
publication_short: "In *EB*"

abstract: "In this article we present an unsupervised low-frequency method aimed at detecting and disaggregating the power used by Cumulative Water Heaters (CWH) in residential homes. Our model circumvents the inherent difficulty of unsupervised signal disaggregation by using both the shape of a power spike and its temporal pattern to identify the contribution of CWH reliably. Indeed, many CHWs in France are configured to turn on automatically during off-peak hours only, and we are able to use this domain knowledge to aid peak identification despite the low sampling frequency.

In order to test our model, we equipped a home with sensors to record the ground truth consumption of a water heater. We then apply the model to a larger dataset of energy consumption of Hello Watt users consisting of one month of consumption data for 5 k homes at 30-min resolution. In this dataset we successfully identified CWHs in 66.5% of cases where consumers declared using them. Inability of our model to identify CWHs in the consumption signal in the remaining cases is likely due to possible misconfiguration of CWHs, since triggering them during off-peak hours requires specific wiring in the electrical panel of the house. Our model, despite its simplicity, offers promising applications: detection of mis-configured CWHs on off-peak contracts and slow performance degradation." 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [NILM]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/abs/pii/S0378778822003711'
url_pdf:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
