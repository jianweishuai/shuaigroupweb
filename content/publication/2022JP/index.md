---
title: 'MSSort-DIA XMBD: A deep learning classification tool of the peptide precursors quantified by OpenSWATH'

authors:
  - Yiming Li
  - Qingzu He
  - Huan Guo
  - Chuan-Qi Zhong
  - Xiang Li
  - Yulin Li
  - Jianwei Shuai
author_notes:
  - 
  - 
  - 
  - 
  - Corresponding author
  - Corresponding author
  - Corresponding author

date: '2022-02-26T00:00:00Z'
doi: '10.1016/j.jprot.2022.104542'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-19T0 0:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication:  J Proteomics. 2022.
publication_short: 

abstract:  OpenSWATH is an analysis toolkit commonly used for data independent acquisition (DIA). Although the output of OpenSWATH is controlled at 1% false discovery rate (FDR), the output report still contains many peptide precursors with low similarity fragments. At the last step of OpenSWATH for peptide quantification, researchers usually need to manually check the similarity of the extracted ion chromatograms (XICs) of fragments to distinguish the high confidence and the low confidence peptide precursors. Here we developed an algorithm with a Graphic User Interface named MSSort-DIAXMBD, which combines the deep convolutional neural network (CNN) and the double-threshold segmentation process, to automatically recognize the high confidence precursors and low confidence precursors. To train the model of MSSort-DIAXMBD, we built a database contained about 50,000 manually classified peptide precursors acquired from different instrument platforms and different species. With the double-threshold segmentation strategy, MSSort-DIAXMBD can reduce the number of the low confidence peptides required for manual inspections to less than 10% and be used as the last step of OpenSWATH to visualize and classify the MS/MS data of peptide precursors. <br/> **SIGNIFICANCE:** Although the output of OpenSWATH is controlled at 1% false discovery rate (FDR), the output report still contains many peptide precursors with low similarity fragments. At the last step of OpenSWATH for peptide quantification, researchers usually need to manually check the similarity of fragment XICs to distinguish the high confidence and the low confidence peptide precursors. However, manual inspection is inefficient. For instance, it takes about 50 h to sort even a small dataset of 1000 MS/MS spectra manually. In this paper we developed a software named MSSort-DIAXMBD to automatically recognize the high confidence precursors. We manually classify 50,000 peptide precursors as training set to train a convolutional neural network. After training finished, MSSort-DIAXMBD takes only a few minutes to automatically classify 20,000 peptide precursors, leaving a small portion of fuzzy ones for manual inspection. On the benchmarked dataset, MSSort-DIAXMBD can significantly improve the efficiency and accuracy of recognition of high confidence peptide precursors.<br/>**Keywords:** Data-independent acquisition proteomics; Deep convolutional neural networks; Deep learning; OpenSWATH.

# Summary. An optional shortened abstract.
summary: 

tags:
  - 
featured: False


url_pdf: /publication/2022JP/2022JP.pdf

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


