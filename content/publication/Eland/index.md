---
title: 'Action sequence augmentation for early graph-based anomaly detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tong Zhao
  - Bo Ni
  - Wenhao Yu
  - Zhichun Guo
  - Neil Shah
  - Meng Jiang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2019-10-01'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM International Conference on Information & Knowledge Management*
publication_short: In *CIKM*

abstract: The proliferation of web platforms has created incentives for online abuse. Many graph-based anomaly detection techniques are proposed to identify the suspicious accounts and behaviors. However, most of them detect the anomalies once the users have performed many such behaviors. Their performance is substantially hindered when the users’ observed data is limited at an early stage, which needs to be improved to minimize financial loss. In this work, we propose Eland, a novel framework that uses action sequence augmentation for early anomaly detection. Eland utilizes a sequence predictor to predict next actions of every user and exploits the mutual enhancement between action sequence augmentation and user-action graph anomaly detection. Experiments on three realworld datasets show that Eland improves the performance of a variety of graph-based anomaly detection methods. With Eland, anomaly detection performance at an earlier stage is better than non-augmented methods that need significantly more observed data by up to 15% on the Area under the ROC curve.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2010.10016.pdf'
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

<!-- [pdf](https://dl.acm.org/doi/pdf/10.1145/3340531.3411981)[code](https://github.com/zhichunguo/GraSeq) -->
<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
