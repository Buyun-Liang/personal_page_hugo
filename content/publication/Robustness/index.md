---
title: 'On Optimization and Optimizers in Adversarial Robustness'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hengyue Liang
  - buyun
  - Ying Cui
  - Tim Mitchell
  - Ju Sun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In submission to IEEE Transactions on Pattern Analysis and Machine Intelligence, 2022 
publication_short: In submission to IEEE Transactions on Pattern Analysis and Machine Intelligence, 2022 

abstract: Empirical evaluation of neural network models against adversarial perturbations entail solving nontrivial constrained optimization problems. Practical algorithms rely on numerical methods such as projected gradient and iterative linearization to find suboptimal points, leading to overestimation of the robust accuracy. To reliably solve these problems, we describe an algorithmic framework that blends a state-of-the-art constrained-optimization solver PyGRANSO, with a constraint-folding technique, called PWCF. PWCF can handle general attack models that are inaccessible to existing algorithms. Empirically, PWCF finds good-quality solutions with reasonable speed. Moreover, we explore the distinct patterns of the solutions found with various combinations of the loss, distance, and optimization algorithm, and discuss the implications of these patterns on robustness evaluation.  

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ICCOPT22 Slides
  url: '/ICCOPT22-NCVX.pdf'

# url_pdf: 'https://arxiv.org/abs/2111.13984'
# url_code: 'https://github.com/sun-umn/NCVX'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/paper/robustness/Robustness_slides.pdf'
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
