---
layout: page
permalink: /teaching/
title: Teaching
# description: Materials for courses you taught. Replace this text with your description.
nav: true
horizontal: false
#display_categories: [ Work] #, fun]
nav_order: 3
---

<!-- For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->
List of courses, projects and internships I have been involved in.
### Courses


### Courses

#### Year 2021-2022

| Title | Level | Program | TD | TP | TD.eq |
|-------|-------|---------|----|----|-------|
| INFO741 - Embedded Systems | Master 1 | Initial |  | 24 | 16 |
| EASI741 - Random Signals | Master 1 | Initial |  | 12 | 8 |
| INFO642 - Signal and Image | Bachelor 3 | Initial |  | 9 | 6 |
| PROJ641 - Project-Based Learning | Bachelor 3 | Initial | 4 | 7 | 8.67 |
| **Total** |  |  | 4 | 52 | 38.67 |

#### Year 2022-2023

| Title | Level | Program | TD | TP | TD.eq |
|-------|-------|---------|----|----|-------|
| INFO101 - Algorithms | Bachelor 1 | Initial | 1.5 | 14 | 10.83 |
| INFO501 - Number Systems and Algorithms | Bachelor 3 | Initial | 10.5 |  | 10.5 |
| PROJ641 - Project-Based Learning | Bachelor 3 | Initial |  | 0.5 | 0.33 |
| PROJ841 - Project-Based Learning | Master 1 | Initial | 6 | 4 | 8 |
| INFO701 - Python Programming (IAE Annecy) | Bachelor 3 | Initial | 10.5 |  | 10.5 |
| INFO642 - Signal and Image | Bachelor 3 | Initial |  | 9 | 6 |
| INFO851 - Embedded Systems | Master 1 | Initial |  | 20 | 13.33 |
| **Total** |  |  | 28.5 | 47.5 | 59.5 |

#### Year 2023-2024

| Title | Level | Program | TD | TP | TD.eq |
|-------|-------|---------|----|----|-------|
| INFO101 - Algorithms | Bachelor 1 | Initial | 9 | 12 | 17 |
| INFO501 - Number Systems and Algorithms | Bachelor 3 | Initial | 9 |  | 9 |
| PROJ841 - Project-Based Learning | Master 1 | Initial | 1.5 |  | 1.5 |
| PROJ943 - Project-Based Learning | Master 2 | Initial | 7.5 | 4 | 9 |
| INFO851 - Embedded Systems | Master 1 | Initial |  | 20 | 13.33 |
| INFO941 - Concurrent Programming | Master 2 | Initial |  | 24 | 16 |
| **Total** |  |  | 27 | 60 | 65.83 |

#### Year 2024-2025

| Title | Level | Program | TD | CM | TD.eq |
|-------|-------|---------|----|----|-------|
| EASI844 - Discrete-Time Systems | Master 1 | Initial | 13 | 3 | 17.5 |
| INFO501 - Number Systems and Algorithms | Bachelor 3 | Initial | 9 |  | 9 |
| **Total** |  |  | 22 | 3 | 26.5 |

### Project

- Problem/Project-based Learning (APP): Proposal and supervision of a student project (3rd-4th year of engineering education) in collaboration with [CREA](https://creamontblanc.org/en) (Altitude Ecosystem Research Center).
  Autonomous System SCAR (Snow Cover & Animal Recognition):
  - Physical measurements acquisition (temperature, humidity & brightness)
  - Image acquisition + processing (object detection, snow/greenery ratio)
  - Information transmission via LoRaWAN protocol
  - Real-time visualization of a set of indicators

### Internships

- Master 1 internship (2024, 4 months): Validation and benchmarking of machine learning methods for the characterization of wet snow by SAR imaging: Application to the Grandes Rousses area.<br />
  **Summary:** Implementation of a benchmarking of machine learning methods for snow characterization by SAR imaging from the [D7] dataset.
  - Formatting existing codes for command-line use.
  - Development of new data labeling methods.
  - Improvement of resource exploitation (multi-threading) and cluster usage option.
  - Creation of a website and documentation.<br />
  **Valorisation:** The developed processing chains have been made available with the creation of a dedicated website.<br />
  [The project on GitHub](https://github.com/cortesmc/ML-WetSnowSAR_pipeline_stage)
- 4th-year engineering education internship (2022, 3 months): Proof of concept of snow segmentation in webcam images by deep learning.<br />
  **Summary:** Implementation of snow segmentation solutions in the context of webcam images with a proof of concept on images provided by CREA.
  - Realization of annotation of time series on 3 zones: in high mountain clear (>2000m), in medium mountain clear (between 1000m and 2000m) and in medium mountain in forest.
  - Implementation of deep learning networks dedicated to the segmentation task (U-net), and comparison of the obtained solutions with commonly used segmentation algorithms (thresholding, edge detection, Otsu).<br />
  [The project on Github](https://github.com/AlexandreProthin/SegmentationNeige/)
- Bachelor's degree internship (Brazil collaboration, 2023, 3 months): Wavelet Change Detection of Urban Areas in Multi-temporal Satellite Images and Supervised Classification of Change Detection Maps.<br />
  **Summary:** In collaboration with Brazil (Aluisio Pinheiro, University of Campinas, Pr), improvement of a wavelet-based change detection method for the analysis of time series of satellite images (WECS), and development of a supervised classification method for the obtained change maps.
  - Processing of two time series of Sentinel-1 satellite images on Mexico and Reunion.
  - Improvement of the WECS method, by taking into account two scales (global and local) for change detection.
  - Use of the maps obtained by WECS on Reunion for the supervised classification of detected changes.<br />
  [The project on Github](https://github.com/Matthieu-Gallet/WECS_local_classification).