---
title: "An example journal article"
authors:
- admin
- Zongxu Pan
- Bin Lei
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: "10.3390/rs9090907"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Tremendous progress has been made in object recognition with deep convolutional neural networks (CNNs), thanks to the availability of large-scale annotated dataset. With the ability of learning highly hierarchical image feature extractors, deep CNNs are also expected to solve the Synthetic Aperture Radar (SAR) target classification problems. However, the limited labeled SAR target data becomes a handicap to train a deep CNN. To solve this problem, we propose a transfer learning based method, making knowledge learned from sufficient unlabeled SAR scene images transferrable to labeled SAR target data. We design an assembled CNN architecture consisting of a classification pathway and a reconstruction pathway, together with a feedback bypass additionally. Instead of training a deep network with limited dataset from scratch, a large number of unlabeled SAR scene images are used to train the reconstruction pathway with stacked convolutional auto-encoders (SCAE) at first. Then, these pre-trained convolutional layers are reused to transfer knowledge to SAR target classification tasks, with feedback bypass introducing the reconstruction loss simultaneously. The experimental results demonstrate that transfer learning leads to a better performance in the case of scarce labeled training data and the additional feedback bypass with reconstruction loss helps to boost the capability of classification pathway.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2072-4292/9/9/907
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
