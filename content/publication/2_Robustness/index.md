---
title: 'Optimization for Adversarial Robustness Evaluations and Implications from the Solution Patterns'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hengyue Liang
  - buyun
  - Le Peng
  - Ying Cui
  - Tim Mitchell
  - Ju Sun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Under review at International Journal of Computer Vision (IJCV)
publication_short: Under review at International Journal of Computer Vision (IJCV)

abstract: Empirical evaluation of deep learning models against adversarial perturbations entails solving nontrivial constrained optimization problems. Existing numerical algorithms commonly used in practice to solve these problems predominantly rely on using projected gradient methods and mostly handle perturbations modeled by ℓ1, ℓ2 and ℓ∞ distance metrics. In this paper, we introduce a novel algorithmic framework that blends a general-purpose constrained-optimization solver PyGRANSO With Constraint-Folding (PWCF), which can add more reliability and generality to the state-of-the-art (SOTA) algorithms (e.g., AutoAttack). Regarding reliability, PWCF provide solutions with stationarity measures to assess the solution quality, and is generally free from delicate hyperparameter tuning. For generality, PWCF can handle much more general perturbation models (e.g., modeled by any piece-wise differentiable metric) which are inaccessible to the existing project gradient methods. With PWCF, we further explore the distinct solution patterns found by various combinations of losses, perturbation models, and optimization algorithms used in robustness evaluation, and discuss the possible implications of these patterns on the current robustness evaluation and adversarial training.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'publication/Robustness/2022_TPAMI_Robustness.pdf'
- name: Slides
  url: 'publication/Robustness/Robustness_slides.pdf'

# url_pdf: 'https://arxiv.org/abs/2111.13984'
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
