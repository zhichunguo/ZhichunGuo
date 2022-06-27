---
title: 'GraSeq: Graph and Sequence Fusion Learning fro Molecular Property Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhichun Guo
  - Wenhao Yu
  - Chuxu Zhang
  - Meng Jiang
  - Nitesh V. Chawla

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2019-10-01'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM International Conference on Information & Knowledge Management*
publication_short: In *CIKM*

abstract: With the recent advancement of deep learning, molecular representation learning – automating the discovery of feature representation of molecular structure, has attracted significant attention from both chemists and machine learning researchers. Deep learning can facilitate a variety of downstream applications, including bio-property prediction, chemical reaction prediction, etc. Despite the fact that current SMILES string or molecular graph molecular representation learning algorithms (via sequence modeling and graph neural networks, respectively) have achieved promising results, there is no work to integrate the capabilities of both approaches in preserving molecular characteristics (e.g, atomic cluster, chemical bond) for further improvement. In this paper, we propose GraSeq, a joint graph and sequence representation learning model for molecular property prediction. Specifically, GraSeq makes a complementary combination of graph neural networks and recurrent neural networks for modeling two types of molecular inputs, respectively. In addition, it is trained by the multitask loss of unsupervised reconstruction and various downstream tasks, using limited size of labeled datasets. In a variety of chemical property prediction tests, we demonstrate that our GraSeq model achieves better performance than state-of-the-art approaches.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

[pdf](https://dl.acm.org/doi/pdf/10.1145/3340531.3411981)[code](https://github.com/zhichunguo/GraSeq)
<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
