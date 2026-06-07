---
title: 'Addressing Extra Voices and Background Noise in Continuous Speech Monitoring: A Case Study on Chronic Obstructive Pulmonary Disease'
authors: 
- salaar_liaqat
- Daniyal Liaqat
- Tatiana Son
- Robert Wu
- Andrea Gershon
- delara
- mariakakis
venue: $PERCOM$
date: 2026-03-19
link: https://doi.org/10.1109/PerCom67906.2026.11524535
thumbnail: /images/pubs/copd_extra_voices.png
abstract: |
  Continuous speech monitoring using smartphones and smartwatches offers numerous opportunities to detect and predict health deterioration. However, the algorithms used to deliver these benefits must account for the realities of periodic audio recording in the wild, including other voices and overlapping noise. To address the former without clean sample voice recordings, we use speaker diarization to identify the person who speaks the most throughout a given day. To address the latter without compromising the validity of extracted speech features, we leverage the intuition that a reliable feature should remain unaltered by a noise-reduction technique when background noise is minimal. We examine both techniques in the context of a longitudinal dataset collected from 16 patients with chronic obstructive pulmonary disease (COPD) over roughly 3 months. Our best model achieved an AUROC of 0.86 when predicting the presence of respiratory symptoms, outperforming baseline models that rely solely on voice activity detection and noise reduction.
theme:
- Passive Sensing
health_topic:
- Respirology
device:
- Smartwatch
skills:
- Digital Signal Processing
- Machine Learning
---
