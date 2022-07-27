---
title: 'NCVX: A General-Purpose Optimization Solver for Machine Learning, and Practical Tricks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - buyun
  - Tim Mitchell
  - Ying Cui
  - Ju Sun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-25T00:00:00Z'
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

abstract: Optimizing nonsmooth problems, especially those with nonsmooth constraints, is hard -- a nonsmooth problem is usually not differentiable at its minimizers, and problems with complicated constraints cannot be handled by the typical structured methods. Although the nonsmooth constrained problem is a curse in optimization, it is a blessing in machine learning and deep learning. Many machine and deep learning problems involve nonsmoothness due to the existence of nonsmooth activation function in the neural network architecture, and also have constraints due to various reasons -- the adversarial training of visual recognition tasks involves nonsmooth constraints to ensure the generated image is not far away from the original one; the physics informed neural networks represent the boundary conditions in the physics problems as the constraints; the orthogonal constraints on the recurrent kernel play an important role in preventing gradient exploding and vanishing in RNN. In this paper, we will introduce our recent research about the importance of this type of problem and how to solve them.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://arxiv.org/abs/2111.13984'
# url_code: 'https://github.com/sun-umn/NCVX'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/ICCOPT22-NCVX.pdf'
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
