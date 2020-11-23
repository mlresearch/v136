---
title: Interpretable Epilepsy Detection in Routine, Interictal EEG Data using Deep
  Learning
abstract: Epilepsy, a common serious neurological disorder, is characterized by its
  frequently occurring seizures that cause its patients to be three times as likely
  to die prematurely. While the application of machine learning to EEG recordings
  has enabled the successful prediction of whether and when such seizures will occur,
  the reliable detection of epilepsy during seizure-free periods is lacking. As far
  as the authors are aware, this work proposes the first deep learning approach for
  the latter task – and the second machine learning approach altogether. Additionally,
  it does so in an interpretable fashion to validate the proposed method for a more
  wide-spread adoption in healthcare and to potentially unveil unknown epileptic biomarkers.
  The performance of the Tiny Visual Geometry Group (t-VGG) convolutional neural network
  is evaluated against Temple University Hospital’s \textit{EEG Epilepsy Corpus},
  a data set of variable-length EEG recordings gathered during routine checkups. The
  t-VGG network predicted individual $10$ second EEG windows with an Area Under the
  Precision-Recall Curve (AUPR) of $93.02%$ for epileptic predictions and $55.85%$
  for healthy ones – a significant improvement of respectively $7.24$pp and $18.6$pp
  ($p\!<\!.001$) over the current state-of-the-art.  Averaging window predictions
  per recording improved the t-VGG’s respective AUPR performances further to $95.52%$
  and $77.27%$. The Gradient-weighted Class Activation Mapping method for interpretability
  confirmed that the model was able to learn sensible features with connections to
  well-known epilepsy markers.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: uyttenhove20a
month: 0
tex_title: Interpretable Epilepsy Detection in Routine, Interictal EEG Data using
  Deep Learning
firstpage: 355
lastpage: 366
page: 355-366
order: 355
cycles: false
bibtex_author: Uyttenhove, Thomas and Maes, Aren and Steenkiste, Tom Van and Deschrijver,
  Dirk and Dhaene, Tom
author:
- given: Thomas
  family: Uyttenhove
- given: Aren
  family: Maes
- given: Tom Van
  family: Steenkiste
- given: Dirk
  family: Deschrijver
- given: Tom
  family: Dhaene
date: 2020-11-23
address: 
container-title: Proceedings of the Machine Learning for Health NeurIPS Workshop
volume: '136'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 11
  - 23
pdf: http://proceedings.mlr.press/v136/uyttenhove20a/uyttenhove20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
