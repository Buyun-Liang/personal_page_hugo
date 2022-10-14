---
title: ' NCVX: A General-Purpose Optimization Solver for Constrained Machine and Deep Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - buyun
  - Tim Mitchell
  - Ju Sun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-10-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Submitted to NeurIPS Workshop on Optimization for Machine Learning (OPT 2022)
publication_short: Submitted to NeurIPS Workshop on Optimization for Machine Learning (OPT 2022)

abstract: Optimizing nonconvex (NCVX) problems, especially nonsmooth and constrained ones, is an essential part of machine learning. However, it can be hard to reliably solve such problems without optimization expertise. Existing general-purpose NCVX optimization packages are powerful but typically cannot handle nonsmoothness. GRANSO is among the first optimization solvers targeting general nonsmooth NCVX problems with nonsmooth constraints, but, as it is implemented in MATLAB and requires the user to provide analytical gradients, GRANSO is often not a convenient choice in machine learning (especially deep learning) applications. To greatly lower the technical barrier, we introduce a new software package called NCVX, whose initial release contains the solver PyGRANSO, a PyTorch-enabled port of GRANSO incorporating auto-differentiation, GPU acceleration, tensor input, and support for new QP solvers. NCVX is built on freely available and widely used open-source frameworks, and as a highlight, can solve general constrained deep learning problems, the first of its kind. NCVX is available at https://ncvx.org/, with detailed documentation and numerous examples from machine learning and other fields.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://arxiv.org/abs/2210.00973
# - name: Website
#   url: https://ncvx.org/


url_pdf: ''
# url_code: 'https://github.com/sun-umn/NCVX'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
