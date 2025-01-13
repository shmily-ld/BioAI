---
title: 'KGNN: Knowledge Graph Neural Network for Drug-Drug Interaction Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lin, Xuan
  - Quan, Zhe
  - Wang, Zhi-Jie
  - Ma, Tengfei 
  - Xiangxiang Zeng

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '01 Jul 2020'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '01 Jul 2020'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Drug-drug interaction (DDI) prediction is a challenging problem in pharmacology and clinical application, and effectively identifying potential DDIs during clinical trials is critical for patients and society. Most of existing computational models with AI techniques often concentrate on integrating multiple data sources and combining popular embedding methods together. Yet, researchers pay less attention to the potential correlations between drug and other entities such as targets and genes. Moreover, recent studies also adopted knowledge graph (KG) for DDI prediction. Yet, this line of methods learn node latent embedding directly, but they are limited in obtaining the rich neighborhood information of each entity in KG. To address the above limitations, we propose an end-to-end framework, called Knowledge Graph Neural Network (KGNN), to resolve the DDI prediction. Our framework can effectively capture drug and its potential neighborhoods by mining their associated relations in KG. To extract both high-order structures andsemantic relations of the KG, we learn from the neighborhoods for each entity in KG as their local receptive, and then integrate neighborhood information with bias from representation of the current entity. This way, the receptive field can be naturally extended to multiple hops away to model highorder topological information and to obtain drugs potential long-distance correlations. We haveimplemented our method and conducted experiments based on several widely-used datasets. Empirical results show that KGNN outperforms the classic and state-of-the-art models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
