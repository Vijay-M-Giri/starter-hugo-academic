---
title: "Asynchronous kernel ridgeless regression"
authors:
- admin
- Mikhail Belkin
- Parthe Pandit
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Kernel machines are a class of predictors commonly used in machine learning. We propose a parallel and completely lock-free asynchronous algorithm, AsyncEigenPro, for kernel regression. This algorithm resembles Hogwild! but uses the special structure of the kernel regression problem. The main application of the algorithm is to enable efficient multi-GPU training for kernel methods. We show theoretically that the effect of delayed gradients and inconsistent reads on the rate of convergence can be minimal. We run large scale experiments to show near linear speedup in training time with respect to the number of GPUs.

# Summary. An optional shortened abstract.
summary: 

tags:
- kernels 
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: ''
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
