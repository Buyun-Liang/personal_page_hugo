---
title: 'Neural Topology Optimization with Principled Constrained Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - buyun
  - Ryan de Vera
  - Hengyue Liang
  - Ying Cui
  - Tim Mitchell
  - Qizhi He
  - Ju Sun

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-03-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In preparation for Structural and Multidisciplinary Optimization
publication_short: In preparation for Structural and Multidisciplinary Optimization

abstract: Topology optimization (TO) is a mathematical approach to mechanical and multiphysics design with the objective of maximizing structural performance under physical and manufacturing constraints. However, applying conventional TO to the design of metamaterials remains challenging due to the existence of implicit physical constraints, combinatorial constraints, and nonlinear physical constraints. Thus, we proposed a user-friendly TO computing framework for general nonlinear metamaterial design. Our contributions included proposing and implementing the TO computing framework and benchmarking its performance. The framework shows advantages in tackling the following difficulties. 1). Implicit Physical Constraints---the manufacturable structure should not have spatially isolated components, but classical methods never explicitly formulated it. Thus, we use the deep image prior (DIP) technique to reparameterize the optimization variables, which is expected to bias toward spatially smooth structures; 2). Combinatorial Constraints---we designed a generalized straight-through technique and its equivalent reformulation to deal with the combinatorial constraint; 3). Nonlinear Physical Constraints---SOTA methods can not handle nonlinear physical constraints. Our TO computing framework successfully solved various design problems including multi-story buildings and supporting bridges with SOTA compliance (i.e., the objective function in TO) and guaranteed feasibility.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Optimization","AI4Science"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: ICCOPT22 Slides
#   url: 'publication/NCVX_exp/ICCOPT22-NCVX.pdf'

# url_pdf: 'https://arxiv.org/abs/2111.13984'
# url_code: 'https://github.com/sun-umn/NCVX'
url_dataset: ''
url_poster: ''
url_project: ''
# url_slides: 'publication/Robustness/Robustness_slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
