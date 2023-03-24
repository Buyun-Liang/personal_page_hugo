---
title: 'NCVX: A General-Purpose Optimization Solver for Machine Learning, and Practical Techniques'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - buyun
  - Wenjie Zhang
  - Hengyue Liang
  - Tim Mitchell
  - Ying Cui
  - Ju Sun

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-03-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In preparation for IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
publication_short: In preparation for IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)

abstract: Constraints are new and increasingly trendy in machine and deep learning, stimulated by, e.g., neuro-symbolic AI that tries to incorporate knowledge and reasoning, scientific applications that need to respect physical laws and constraints, and trustworthy AI that performs robust optimization over complicated perturbation sets. However, optimization expertise is necessary to reliably solve such problems. In practice, people usually try to avoid complicated constraints, and if constraints cannot be avoided, people may use naive methods to handle constraints. To lower the technical barrier for constrained machine and deep learning, we introduced our software package called NCVX, whose initial release contains the solver PyGRANSO, a PyTorch-enabled port of GRANSO incorporating auto-differentiation, GPU acceleration, tensor input, and support for new QP solvers. This software package is the first of its kind to solve deep learning problems with highly nontrivial, usually nonsmooth, constraints. We show on a wide variety of constrained machine and deep learning problems that our NCVX PyGRANSO is powerful enough to deal with any complicated constraints, which even involves neural networks. We also provided practical techniques such as reparameterization, constraints folding and problem rescaling to speed up convergence of NCVX PyGRANSO.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Selected", "Optimization"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Website
  url: https://ncvx.org/
- name: ICCOPT22 Slides
  url: 'publication/NCVX_exp/ICCOPT22-NCVX.pdf'
- name: SDM2023 Tutorial
  url: 'publication/NCVX_exp/2023_SDM_PyGRANSO_Tutorial.pdf'
- name: ICASSP 2023 Tutorial
  url: 'publication/NCVX_exp/2023_ICASSP_PyGRANSO_Tutorial.pdf'

# url_pdf: 'https://arxiv.org/abs/2111.13984'
# url_code: 'https://github.com/sun-umn/NCVX'
url_dataset: ''
url_poster: ''
url_project: ''
# url_slides: '/ICCOPT22-NCVX.pdf'
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
