---
title: 'Neural Topology Optimization Based on Differential Programming With Principled Constrained Optimization '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ryan de Vera
  - buyun
  - Binyao Guo
  - Qizhi He
  - Ju Sun

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-12-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In ASME 2024 International Mechanical Engineering Congress and Exposition (IMECE2024) 
publication_short: In ASME 2024 International Mechanical Engineering Congress and Exposition (IMECE2024) 

abstract: "Topology optimization (TO) seeks to determine the optimal distribution of material within a specified design domain for maximizing the structural performance while adhering to predefined constraints. Recent advancements in deep learning and neural network representations have shown significant promise in approximating PDE solutions, opening up a new avenue for synergy between these technologies and TO. In this study, we introduce a differential programming-based TO framework that leverages   effective non-convex optimization with the deep image prior (DIP) approach for the re-parameterization of the density field, with a focus on addressing the inherent challenges of TO due to combinatorial constraints. The proposed TO algorithm is developed based on a in-house non-convex optimization algorithm PyGranso, which provides a robust optimization method with the ability to handle non-convex, non-smooth and non-linear constrained optimization problems; thus, it enables higher effectiveness in navigating the complex constraint space for TO problems and enabling the discovery of optimal designs. Furthermore, the employment of DIP to parameterize the density field enhances the capacity of design representation and enforces higher smoothness as it leverages the latent structure of convolutional neural networks (CNNs). Compared with other (conventional and machine learning based) TO methods, our experimental results demonstrate the superiority of our proposed framework, especially in accurately preserving the constraints. By systematically evaluating its performance across a range of classical TO problems, including (1) MBB beam, (2) complex cases such as L-shaped structures with tricky loading paths, and (3) situations requiring the use of multiple materials in one design, the MBB beam, L-shaped structure with complex loading path, and the multi-material design problem, we have shown that our approach not only yields improved  design  in terms of material efficiency and structural integrity but also significantly enhances the feasibility of the optimization solutions. Our evaluation of TO methods is based on three key metrics: objective function (compliance), binary constraint adherence and volume constraint adherence. We compare our proposed method against the established Solid Isotropic Material with Penalization (SIMP) approach coupled with the Method of Moving Asymptotes (MMA). For example, in the case of the Cantilever Beam, MMA achieves a compliance of 255.66, incurs a binary constraint violation of 0.0609, and meets the volume constraint at 0.0. In contrast, our method achieves an improved compliance of 223.65 with zero violations in both binary and volume constraints. These results are consistent across various structures, highlighting our method’s ability to generate stiff and feasible designs."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["AI4Science"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: IMECE2024 Page
  url: 'https://imece.secure-platform.com/a/solicitations/236/sessiongallery/18040/application/144057'

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
