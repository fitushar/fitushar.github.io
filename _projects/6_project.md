---
layout: page
title: ReFINE-Lung
description: REcalibration and False positive INference Engine for Consensus-Based Lung Nodule Detection
img: assets/img/RrFinelung_fig1.png
importance: 2
category: work
redirect: https://fitushar.github.io/ReFINELung.github.io/
related_publications: true
---
Project page:[https://fitushar.github.io/ReFINELung.github.io/](https://fitushar.github.io/ReFINELung.github.io/)

The clinical utility of AI models trained on simulated or publicly annotated datasets hinges on their ability to generalize to large-scale, real-world imaging data—an enduring challenge due to the high cost and complexity of expert annotations. To address this, we introduce ReFINE-Lung, a modular, consensus-driven framework for curating high-quality pseudo-labels from unannotated clinical lung CT scans. ReFINE-Lung begins with ensemble-based nodule candidate generation using diverse AI models trained on simulated, public, and institutional data. It then refines predictions through a four-stage ReFINE Block: (1) affine calibration of model outputs, (2) unsupervised prediction alignment to the clinical data distribution, (3) disease prevalence estimation via kernel density modeling, and (4) cost-sensitive thresholding. By combining multi-model agreement with morphological filters and statistical corrections, ReFINE-Lung produces scalable, trustworthy pseudo-labels that reduce false positives and enhance generalizability across clinical domains. This framework lays the foundation for semi-supervised training, domain adaptation, and external benchmarking of lung nodule detection systems in real-world screening environments.

Collaborators
Fakrul Islam Tushar (lead scientist), Joseph Y Lo (PI)

Skills: Artificial Intelligence (AI) · Medical Imaging · Project Management · Image Processing




.


