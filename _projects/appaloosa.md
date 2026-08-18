---
layout: page
title: APPALOOSA
description: APPALOOSA explores self-supervised representation learning for Synthetic Aperture Radar (SAR) time series. Classical pretext tasks rely on Euclidean or Gaussian assumptions that poorly capture the multiplicative speckle noise and heavy-tailed statistics of SAR data. The project integrates robust similarity measures between non-Gaussian distributions (Kullback-Leibler, Rényi, Wasserstein) into differentiable, temporally-aligned cost functions, extended to multivariate polarimetric data. The resulting representations are validated on simulated, Sentinel-1, PAZ and InSAR SAR time series for classification and segmentation tasks, in a joint project between LISTIC and ICube laboratories.
img: assets/img/appaloosa-project.png
importance: 1
category: Projets portés
---

**APPALOOSA** — *ApPrentissage de rePrésentAtions par simiLarité rObuste avec a-priOri StAtistiques* — is an exploratory project funded by the **GDR ISIS** (2026 call for exploratory projects), carried out jointly by the **LISTIC** laboratory (Université Savoie Mont Blanc) and **ICube** (Université de Strasbourg).

### Context

Self-supervised learning builds latent representations without costly manual annotations, but classical pretext tasks rely on statistical and geometric assumptions (Euclidean distances, Gaussian noise) that poorly fit data from active sensors such as Synthetic Aperture Radar (SAR). SAR time series enable continuous monitoring of the Earth's surface regardless of weather or lighting conditions, but their exploitation is hampered by geometric distortions and a strong multiplicative noise (speckle), which requires modeling with heavy-tailed, non-Gaussian distributions (compound-Gaussian, Weibull).

### Objectives and approach

The project explores the integration of robust statistical similarity measures between non-Gaussian distributions into a self-supervised learning framework for SAR time series. The work is organized around three main directions:

- Deriving differentiable formulations of similarity metrics between non-Gaussian distributions (Kullback-Leibler, Rényi, Wasserstein), combined with temporal-alignment algorithms such as soft-DTW.
- Extending these metrics to the multivariate case to account for polarimetric information.
- Designing self-supervised pretext tasks (contrastive learning, masked reconstruction) built around these robust metrics rather than standard distances.

The approaches will be validated on complementary SAR datasets — simulated data (ONERA), Sentinel-1 time series, high-resolution PAZ acquisitions over the Mont-Blanc massif, and the ISSLIDE InSAR dataset — for classification and segmentation tasks.

### Partners

- **LISTIC**, Université Savoie Mont Blanc — Matthieu Gallet, Yassine Mhiri
- **ICube**, Université de Strasbourg — Antoine Bralet (project coordinator)

### Timeline

The project runs over 18 months, from methodological development to validation on real data, including the co-supervision of a Master 2 internship and dissemination through an international conference and national workshops (GRETSI, GDR ISIS days). The resulting code will be released as open source.
