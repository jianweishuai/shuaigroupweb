---
title: 'Predicting potential interactions between lncRNAs and proteins via combined graph auto-encoder methods'
authors:
  - Jingxuan Zhao
  - Jianqiang Sun
  - Stella C. Shuai
  - Qi Zhao
  - Jianwei Shuai
date: '2023-01-19T00:00:00Z'
doi: '10.1093/bib/bbac527'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-19T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Briefings in Bioinformatics, 2023, 24(1), 1–9
publication_short: 

abstract: Long noncoding RNA (lncRNA) is a kind of noncoding RNA with a length of more than 200 nucleotide units. Numerous research studies have proven that although lncRNAs cannot be directly translated into proteins, lncRNAs still play an important role in human growth processes by interacting with proteins. Since traditional biological experiments often require a lot of time and material costs to explore potential lncRNA–protein interactions (LPI), several computational models have been proposed for this task. In this study, we introduce a novel deep learning method known as combined graph auto-encoders (LPICGAE) to predict potential human LPIs. First, we apply a variational graph auto-encoder to learn the low dimensional representations from the high-dimensional features of lncRNAs and proteins. Then the graph auto-encoder is used to reconstruct the adjacency matrix for inferring potential interactions between lncRNAs and proteins. Finally, we minimize the loss of the two processes alternately to gain the final predicted interaction matrix. The result in 5-fold cross-validation experiments illustrates that our method achieves an average area under receiver operating characteristic curve of 0.974 and an average accuracy of 0.985, which is better than those of existing six state-of-the-art computational methods. We believe that LPICGAE can help researchers to gain more potential relationships between lncRNAs and proteins effectively.

# Summary. An optional shortened abstract.
summary: 

tags:
  - 
featured: False


url_pdf: http://localhost:1313/ShauijianweiGroup/publication/zhaoq-bib/2023-ZhaoQ-BiB.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


