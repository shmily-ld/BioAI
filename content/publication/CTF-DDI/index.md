---
title: 'CTF-DDI: Constrained tensor factorization for drug--drug interactions prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guosheng Han 
  - Lingzhi Peng
  - Aocheng Ding
  - Yan Zhang
  - Xuan Lin

author_notes:
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding author'
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2024-07-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['Future Generation Computer Systems']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Computational approaches for predicting drug–drug interactions (DDI) can significantly facilitate combination therapy and drug discovery. Existing similarity-based methods often overlook simple yet valuable structural information or ignore multiple relationships from biological entities (e.g., target proteins and enzymes). Meanwhile, matrix factorization-based methods can alleviate the inherent sparsity issues in DDI data. However, this line of work usually only considers the original association information of DDI pairs. To address these issues, we proposed a novel tensor factorization strategy with effective constraint terms (CTF-DDI) for potential DDI prediction. Specifically, we first obtained drug features by constructing specific similarity matrices based on drug structure and drug-related biological associations. Then, a novel constrained tensor factorization(CTF) module was designed to further reconstruct drug similarity by introducing Hessian and regularization as constraints. Finally, we trained a deep neural network to extract nonlinear features for DDI prediction. Experimental results on two benchmark datasets demonstrated that the proposed CTF-DDI model outperforms classical tensor factorization and deep learning models. Furthermore, ablation and case studies validated the performance of CTF-DDI in DDI prediction. The source code of CTF-DDI is available at https://github.com/angelfacedac/CTF_DDI.
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
