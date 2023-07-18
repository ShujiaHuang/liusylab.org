---
title: "Large-scale inference of population structure in presence of missingness using PCA"

authors:
- Jonas Meisner
- Siyang Liu
- Mingxi Huang
- Anders Albrechtsen

author_notes:
- "Equal contribution"

date: "2021-07-01"
doi: "10.1093/bioinformatics/btab027"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Bioinformatics*"
publication_short: ""

abstract: Principal component analysis (PCA) is a commonly used tool in genetics to capture and visualize population structure. Due to technological advances in sequencing, such as the widely used non-invasive prenatal test, massive datasets of ultra-low coverage sequencing are being generated. These datasets are characterized by having a large amount of missing genotype information. We present EMU, a method for inferring population structure in the presence of rampant non-random missingness. We show through simulations that several commonly used PCA methods cannot handle missing data arisen from various sources, which leads to biased results as individuals are projected into the PC space based on their amount of missingness. In terms of accuracy, EMU outperforms an existing method that also accommodates missingness while being competitively fast. We further tested EMU on around 100K individuals of the Phase 1 dataset of the Chinese Millionome Project, that were shallowly sequenced to around 0.08×. From this data we are able to capture the population structure of the Han Chinese and to reproduce previous analysis in a matter of CPU hours instead of CPU years. EMU's capability to accurately infer population structure in the presence of missingness will be of increasing importance with the rising number of large-scale genetic datasets. 


# Summary. An optional shortened abstract.
summary: ""

tags:
- Interneurons
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://academic.oup.com/bioinformatics/article/37/13/1868/6103565
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
slides:
---
