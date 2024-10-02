---
title: 'XBound-Former: Toward Cross-scale Boundary Modeling in Transformers'
authors:
  - Jiacheng Wang
  - Fei Chen
  - Yuxi Ma
  - Liansheng Wang
  - Zhaodong Fei
  - Jianwei Shuai
  - Xiangdong Tang
  - Qichao Zhou
  - Jing Qin
author_notes:

date: '2023-01-13T00:00:00Z'
doi: '10.1109/TMI.2023.3236037'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'IEEE Transactions on Medical Imaging'
publication_short: ''

abstract: Skin lesion segmentation from dermoscopy images is of great significance in the quantitative analysis of skin cancers, which is yet challenging even for der matologists due to the inherent issues, i.e., considerable size, shape and color variation, and ambiguous bound aries. Recent vision transformers have shown promising performance in handling the variation through global con text modeling. Still, they have not thoroughly solved the problem of ambiguous boundaries as they ignore the com plementary usage of the boundary knowledge and global contexts. In this paper, we propose a novel cross-scale boundary-aware transformer, XBound-Former, to simulta neously address the variation and boundary problems of skin lesion segmentation. XBound-Former is a purely attention-based network and catches boundary knowledge via three specially designed learners. First, we propose an implicit boundary learner (im-Bound) to constrain the network attention on the points with noticeable bound ary variation, enhancing the local context modeling while maintaining the global context. Second, we propose an ex plicit boundary learner (ex-Bound) to extract the boundary knowledge at multiple scales and convert it into embed dings explicitly. Third, based on the learned multi-scale boundary embeddings, we propose a cross-scale bound ary learner (X-Bound) to simultaneously address the prob lem of ambiguous and multi-scale boundaries by using learned boundary embedding from one scale to guide the boundary-aware attention on the other scales. We evaluate the model on two skin lesion datasets and one polyp lesion dataset, where our model consistently outperforms other convolution- and transformer-based models, especially on the boundary-wise metrics. 

# Summary. An optional shortened abstract.
summary: 

tags:
  - 
featured: False

# links:
# - name: ""
#   url: ""
url_pdf: /publication/2023 WangLS-IEEE/2023 WangLS-IEEE.pdf
url_code: http://github.com/jcwang123/xboundformer
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
  preview_only: False

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
slides:
---

