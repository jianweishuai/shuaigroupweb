---
title: 'Machine-learning micropattern manufacturing'
authors:
 - Si Wanga
 - Ziao Shena
 - Zhenyu Shena
 - Yuanjun Donga
 - Yanran Lia
 - Yuxin Caoa
 - Yanmei Zhangb
 - Shengshi Guoa
 - Jianwei Shuaia
 - Yun Yanga
 - Changjian Linb
 - Xun Chenc
 - Xingcai Zhangd- 
 - Qiaoling Huanga

author_notes:
 - 
 - 
 - 
 - 
 - 
 - 
 - 
 - 
 - 
 - 
 - 
 - Corresponding author
 - Corresponding author- 
 - Corresponding author

date: '2021-04-175T00:00:00Z'
doi: 'https://doi.org/10.1016/j.nantod.2021.10115'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-04-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Nano Today 38 (2021) 101152
publication_short: 

abstract: Micropatterning has been widely applied in electronics, biomaterials engineering, and microfluidics studies. A key challenge in using bipolar electrochemistry for fabricating titanium dioxide (TiO2) nanotube micropatterns (TNMs) with desired properties is to balance interrelated experimental parameters and define experimental boundary conditions. For example, it is challenging to determine the anodization voltage boundary as high anodization voltage with certain conditions might induce titanium foils rupture. Here, we utilize active learning to facilitate the optimization process of fabricating TNMs with a wide dimension range within one sample using bipolar electrochemistry. Starting with a small dataset, the decision tree model differentiates normal data from abnormal data (i.e., titanium foils ruptured), which helps define the experimental boundaries. Then gradient boosted regression tree (GBRT) model analyzes the data and provides predictions and directions for optimizing TNMs. Then predictions are verified by experiments, and new results update the training dataset for the next learning loop. Results show that ML algorithms well define the experimental boundary conditions. And only within several iterations, we obtained the optimal TNMs with a diameter range of 27–470 nm, expanding the gradient to the largest extend without tedious experiments. Those results indicate that machine learning algorithms are effective in accelerating materials manufacture and optimization. Further silver nanoparticle doping demonstrates that large-scale TNMs are effective platforms for high-throughput screening. 



# Summary. An optional shortened abstract.
summary: 1

tags:
  - 
featured: False


url_pdf: /publication/2021NanoToday/2021NanoToday.pdf
# url_code: https://github.com/jianweishuai/TCS
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


