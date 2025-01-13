---
title: 'Kg-mtl: knowledge graph enhanced multi-task learning for molecular interaction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tengfei Ma
  - Xuan Lin
  - Bosheng Song
  - Philip S Yu 
  - Xiangxiang Zeng

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '04 Jul 2022'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '04 Jul 2022'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Molecular interaction prediction is essential in various applications including drug discovery and material science. The problem becomes quite challenging when the interaction is represented by unmapped relationships in molecular networks, namely molecular interaction, because it easily suffers from (i) insufficient labeled data with many false-positive samples, and (ii) ignoring a large number of biological entities with rich information in the knowledge graph. Most of the existing methods cannot properly exploit the information of knowledge graph and molecule graph simultaneously. In this paper, we propose a large-scale K nowledge G raph enhanced M ulti- T ask L earning model, namely KG-MTL, which extracts the features from both knowledge graph and molecular graph in a synergistic way. Moreover, we design an effective Shared Unit that helps the model to jointly preserve the semantic relations of drug entity and the neighbor structures of the compound in both knowledge graph and molecular graph. Extensive experiments on four real-world datasets demonstrate that our proposed KG-MTL outperforms the state-of-the-art methods on two representative molecular interaction prediction tasks drug-target interaction prediction and compound-protein interaction prediction. The source code of KG-MTL is available at https://github.com/xzenglab/KG-MTL.

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
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
