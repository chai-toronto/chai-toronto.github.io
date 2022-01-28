---
title: 'Sleep Sound Classification Using ANC-Enabled Earbuds'
authors: 
- ken_christofferson
- Xuyang Chen
- Zeyu Chang
- mariakakis
- Yuntao Wang
venue: HCCS Workshop, IEEE International Conference on Pervasive Computing and Communications (PerCom), 2022
date: 2022-03-21
# pdf: /pdfs/biliscreen.pdf
image: /images/pubs/sleep_earbuds.jpeg
thumbnail: /images/pubs/sleep_earbuds_thumb.jpeg
caption: By analyzing audio recorded by the in-ear microphone withing commodity earbuds, we demonstrate the feasibility of classifying body sounds associated with sleep disorders.
# citation: |
#     Alex Mariakakis, Megan A. Banks, Lauren Phillipi, Lei Yu, James Taylor, & Shwetak N. Patel. (2017). BiliScreen: Smartphone-Based Scleral Jaundice Monitoring for Liver and Pancreatic Disorders. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 1(2), 20. DOI: http://dx.doi.org/10.1145/3090085
abstract: |
    Standard sleep quality assessment methods require custom hardware and professional observation, limiting the diagnosis of sleep disorders to specialized sleep clinics. In this work, we leverage the internal and external microphones present in active noise-cancelling earbuds to distinguish sounds associated with poor or disordered sleep, thereby enabling continuous at-home sleep monitoring. The sleep sounds our system is able to recognize include, but are not limited to, snoring, teeth grinding, and restless movement. We analyze the resulting dual-channel audio using a lightweight deep learning model built around a variation of the temporal shift module that has been optimized for audio. The model was designed to have a low memory and computational footprint, making it suitable to be run on a smartphone or the earbuds themselves. We evaluate our approach on a dataset of 8 sound categories generated from 20 participants. We achieve a classification accuracy of 91.0% and an F1-score of 0.845.
# bibtex: |
#     @article{mariakakis2017biliscreen,
#     title={BiliScreen: Smartphone-Based Scleral Jaundice Monitoring for Liver and Pancreatic Disorders},
#     author={Mariakakis, Alex and Banks, Megan A and Phillipi, Lauren and Yu, Lei and Taylor, James and Patel, Shwetak N},
#     journal={Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies},
#     volume={1},
#     number={2},
#     pages={20},
#     year={2017},
#     publisher={ACM},
#     url={http://doi.acm.org/10.1145/3090085},
#     doi={10.1145/3090085}
#     }
---
