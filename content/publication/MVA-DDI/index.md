---
title: 'Interpretable multi-view attention network for drug-drug interaction prediction'


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xuan Lin 
  - Qi Wen 
  - Sijie Yang 
  - Zu-Guo Yu 
  - Yahui Long 
  - Xiangxiang Zeng 

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '18 Jan 2024'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '18 Jan 2024'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Drug-drug interaction (DDI) plays an increasingly crucial role in drug discovery. Predicting potential DDI is also essential for clinical research. Given the high cost and risk of wet-lab experiments, in-silico DDI prediction is an alternative choice. Recently, deep learning methods have been developed for DDI prediction. However, most of existing methods focus on feature extraction from either molecular SMILES sequences or drug interactive networks, ignoring the valuable complementary information that can be derived from these two views. In this paper, we propose a novel interpretable Multi-View Attention network (MVA-DDI) for DDI prediction. MVA-DDI can effectively extracts drug representations from different perspectives to improve DDI prediction. Specifically, for a given drug, we design a transformer-based encoder and a graph convolutional networkbased encoder to learn sequence and graph representations from SMILES sequence and molecular graph, respectively. To fully exploit the complementary information between the sequence and molecular views, an attention mechanism is further adopted to adaptively aggregate the sequence and graph representations by taking the importance of different views into accounts, generating the final drug representations. Comparison experiments demonstrated that our MVA-DDI 1 model achieved superior performance to state-of-the-art models on DDI prediction.

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
