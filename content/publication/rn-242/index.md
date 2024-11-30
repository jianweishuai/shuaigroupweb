---
title: 'AttnPep: A Self-Attention-Based Deep Learning Method for Peptide Identification
  in Shotgun Proteomics'
authors:
- Y. Li
- Q. He
- H. Guo
- S. C. Shuai
- J. Cheng
- L. Liu
- J. Shuai
date: '2024-01-01'
publishDate: '2024-11-30T06:55:19.476491Z'
publication_types: ['2']
publication: '*J Proteome Res*'
doi: 10.1021/acs.jproteome.3c00729
abstract: In shotgun proteomics, the proteome search engine analyzes mass spectra
  obtained by experiments, and then a peptide-spectra match (PSM) is reported for
  each spectrum. However, most of the PSMs identified are incorrect, and therefore
  various postprocessing software have been developed for reranking the peptide identifications.
  Yet these methods suffer from issues such as dependency on distribution, reliance
  on shallow models, and limited effectiveness. In this work, we propose AttnPep,
  a deep learning model for rescoring PSM scores that utilizes the Self-Attention
  module. This module helps the neural network focus on features relevant to the classification
  of PSMs and ignore irrelevant features. This allows AttnPep to analyze the output
  of different search engines and improve PSM discrimination accuracy. We considered
  a PSM to be correct if it achieves a q-value <0.01 and compared AttnPep with existing
  mainstream software PeptideProphet, Percolator, and proteoTorch. The results indicated
  that AttnPep found an average increase in correct PSMs of 9.29% relative to the
  other methods. Additionally, AttnPep was able to better distinguish between correct
  and incorrect PSMs and found more synthetic peptides in the complex SWATH data set.
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pubmed/38252705

url_pdf: /shuaigroupweb/publication/rn-242/2024 黎玉林JPR.pdf
---
