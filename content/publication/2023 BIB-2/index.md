---
title: 'Predicting metabolite–disease associations based on
auto-encoder and non-negative matrix factorization'
authors:
  - Hongyan Gao
  - Jianqiang Sun
  - Yukun Wang
  - Yuer Lu
  - Liyu Liu
  - Qi Zhao
  - Jianwei Shuai
author_notes: 
  -  
  -  
  -  
  -  
  -  
  - Corresponding author
  - Corresponding author
date: '2023-07-25T00:00:00Z'
doi: '10.1093/bib/bbad259'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Brief Bioinform. 2023 Jul 18:bbad259
publication_short: 

abstract: Metabolism refers to a series of orderly chemical reactions used to maintain life activities in organisms. In healthy individuals, metabolism remains within a normal range. However, specific diseases can lead to abnormalities in the levels of certain metabolites, causing them to either increase or decrease. Detecting these deviations in metabolite levels can aid in diagnosing a disease. Traditional biological experiments often rely on a lot of manpower to do repeated experiments, which is time consuming and labor intensive. To address this issue, we develop a deep learning model based on the auto-encoder and non-negative matrix factorization named as MDA-AENMF to predict the potential associations between metabolites and diseases. We integrate a variety of similarity networks and then acquire the characteristics of both metabolites and diseases through three specific modules. First, we get the disease characteristics from the five-layer auto-encoder module. Later, in the non-negative matrix factorization module, we extract both the metabolite and disease characteristics. Furthermore, the graph attention auto-encoder module helps us obtain metabolite characteristics. After obtaining the features from three modules, these characteristics are merged into a single, comprehensive feature vector for each metabolite-disease pair. Finally, we send the corresponding feature vector and label to the multi-layer perceptron for training. The experiment demonstrates our area under the receiver operating characteristic curve of 0.975 and area under the precision-recall curve of 0.973 in 5-fold cross-validation, which are superior to those of existing state-of-the-art predictive methods. Through case studies, most of the new associations obtained by MDA-AENMF have been verified, further highlighting the reliability of MDA-AENMF in predicting the potential relationships between metabolites and diseases.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Source Themes
featured: false


url_pdf: /publication/2023 BIB-2/2023 BIB-2.pdf
#url_code: https://github.com/studentiz/dpi

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


