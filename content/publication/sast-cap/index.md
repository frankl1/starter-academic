---
title: "Scalable and Accurate Subsequence Transform for Time Series Classification"
authors:
- admin
- Engelbert MEPHU NGUIFO
date: "2021-06-16"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-16"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conférence sur l'Apprentissage automatique (CAp)*
publication_short: In *CAp*

abstract: Time series classification using phase-independent subsequences called shapelets is one of the best approaches in the state of the art. This approach is especially characterized by its interpretable property and its fast prediction time. However, given a dataset of n time series of length at most m, learning shapelets requires a computation time of O(n 2 m 4) which is too high for practical datasets. In this paper, we exploit the fact that shapelets are shared by the members of the same class to propose the SAST (Scalable and Accurate Subsequence Transform) algorithm which is interpretable, accurate and more faster than the actual state of the art shapelet algorithm. The experiments we conducted on the UCR archive datasets shown that SAST is more accurate than the state of the art Shapelet Transform algorithm on many datasets, while being significantly more scalable.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
url_pdf: 'https://hal.uca.fr/hal-03087686/file/sast.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://cap2021.sciencesconf.org/data/slides12.pdf'
url_source: 'https://hal.uca.fr/hal-03087686'
url_video: 'https://www.youtube.com/watch?v=0_Uhc-2vLGg'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


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
slides: ""
---


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
