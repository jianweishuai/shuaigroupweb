---
title: 'FM-FCN: A Neural Network with Filtering Modules for Accurate Vital Signs Extraction'
authors:
- F. Zhu
- Q. Niu
- X. Li
- Q. Zhao
- H. Su
- J. Shuai
date: '2024-01-01'
publishDate: '2024-11-30T10:33:06.843204Z'
publication_types:
- article-journal
publication: '*Research (Wash D C)*'
doi: 10.34133/research.0361
abstract: Neural networks excel at capturing local spatial patterns through convolutional
  modules, but they may struggle to identify and effectively utilize the morphological
  and amplitude periodic nature of physiological signals. In this work, we propose
  a novel network named filtering module fully convolutional network (FM-FCN), which
  fuses traditional filtering techniques with neural networks to amplify physiological
  signals and suppress noise. First, instead of using a fully connected layer, we
  use an FCN to preserve the time-dimensional correlation information of physiological
  signals, enabling multiple cycles of signals in the network and providing a basis
  for signal processing. Second, we introduce the FM as a network module that adapts
  to eliminate unwanted interference, leveraging the structure of the filter. This
  approach builds a bridge between deep learning and signal processing methodologies.
  Finally, we evaluate the performance of FM-FCN using remote photoplethysmography.
  Experimental results demonstrate that FM-FCN outperforms the second-ranked method
  in terms of both blood volume pulse (BVP) signal and heart rate (HR) accuracy. It
  substantially improves the quality of BVP waveform reconstruction, with a decrease
  of 20.23% in mean absolute error (MAE) and an increase of 79.95% in signal-to-noise
  ratio (SNR). Regarding HR estimation accuracy, FM-FCN achieves a decrease of 35.85%
  in MAE, 29.65% in error standard deviation, and 32.88% decrease in 95% limits of
  agreement width, meeting clinical standards for HR accuracy requirements. The results
  highlight its potential in improving the accuracy and reliability of vital sign
  measurement through high-quality BVP signal extraction. The codes and datasets are
  available online at https://github.com/zhaoqi106/FM-FCN.
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pubmed/38737196
---
