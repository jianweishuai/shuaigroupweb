---
title: '深度神经网络筛选蛋白质组学高置信度定量
肽段'
authors:
  - 郭欢
  - 何情祖
  - 黎玉林
  - 帅建伟
author_notes: 
  -  
  -  
  -  
  - Corresponding author
date: '2023-05-18T00:00:00Z'
doi: '10.12677/biphy.2023.112002'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 生物物理学, 2023, 11(2), 17-29
publication_short: 

abstract: 质谱分析是蛋白质组学的重要研究方法。数据不依赖获取是一种稳定且复现性高的质谱仪数据采集方式，具有质荷比范围宽广，通量高等特点。DIA-NN是处理DIA蛋白质组学数据的主流定量软件之一。由于DIA-NN分析DIA数据后输出的肽段中存在低置信度肽段，生物学家需要根据肽段碎片离子色谱峰组图(XICs)的相似性来人工筛选出高置信度肽段。人工筛选的任务量大、耗时长，并且筛选标准因人而异，这导致结果具有主观性。本文提出了一种名为MSDeepFilter的算法，它基于深度学习技术，能够自动筛选出高置信度的肽段。MSDeepFilter算法结合压缩激励神经网络和残差网络设计深度学习模型，从XICs中提取特征，以此区分高置信度和低置信度肽段。与传统机器学习模型Adaboosting和支持向量机模型相比，MSDeepFilter模型在基准数据集上的多项分类性能指标均表现更优，测试集AUC值达到了98.7%。这表明MSDeepFilter具有优秀性能，可以替代人工筛选的环节

# Summary. An optional shortened abstract.
summary: 

tags:
  - Source Themes
featured: false


url_pdf: /publication/2023BIPHY郭欢/2023BIPHY郭欢.pdf
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


