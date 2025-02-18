---
title: 'Dear-PSM: A deep learning-based peptide search engine enables full database
  search for proteomics'
authors:
- Q. He
- X. Li
- J. Zhong
- G. Yang
- J. Han
- J. Shuai
date: '2024-01-01'
publishDate: '2025-02-18T03:42:02.611396Z'
publication_types:
- article-journal
publication: '*Smart Med*'
doi: 10.1002/SMMD.20240014
abstract: Peptide spectrum matching is the process of linking mass spectrometry data
  with peptide sequences. An experimental spectrum can match thousands of candidate
  peptides with variable modifications leading to an exponential increase in candidates.
  Completing the search within a limited time is a key challenge. Traditional searches
  expedite the process by restricting peptide mass errors and variable modifications,
  but this limits interpretive capability. To address this challenge, we propose Dear-PSM,
  a peptide search engine that supports full database searching. Dear-PSM does not
  restrict peptide mass errors, matching each spectrum to all peptides in the database
  and increasing the number of variable modifications per peptide from the conventional
  3-20. Leveraging inverted index technology, Dear-PSM creates a high-performance
  index table of experimental spectra and utilizes deep learning algorithms for peptide
  validation. Through these techniques, Dear-PSM achieves a speed breakthrough 7 times
  faster than mainstream search engines on a regular desktop computer, with a remarkable
  240-fold reduction in memory consumption. Benchmark test results demonstrate that
  Dear-PSM, in full database search mode, can reproduce over 90% of the results obtained
  by mainstream search engines when handling complex mass spectrometry data collected
  from different species using various instruments. Furthermore, it uncovers a substantial
  number of new peptides and proteins. Dear-PSM has been publicly released on the
  GitHub repository https://github.com/jianweishuai/Dear-PSM.
tags:
- deep learning inverted index mass spectrometry peptide search proteomics
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pubmed/39420951
---
