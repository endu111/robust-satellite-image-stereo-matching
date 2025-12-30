
# Dataset Release

## Overview
Inaccurate or noisy labels have a huge impact on the training of deep learning models. To date, few studies have focused on the label error problem in satellite image stereo matching.

This repository contains corrected datasets from our research paper "RSMT: Robust stereo matching training with geometric correction, clean pixel selection and loss weighting":

(1) Inaccurate-label stereo matching datasets US3D(E) and WHU(E) based on raw datasets.
(2) Accurate-label stereo matching datasets US3D(E) and WHU(E) based on raw datasets. (Although there are still very small residual errors, this version can already be used for accurate evaluation of various studies. We are conducting a study to provide an almost completely accurate satellite image stereo matching dataset, and the upgraded clean dataset is awaited.)

Please find the details below. 

## Dataset Download
Link: https://pan.baidu.com/s/13utnU5C9R7XE6qBVpFcmhA?pwd=79dt Code: 79dt 
- **inaccurate_train**: training datasets for noisy label training tasks
- **clean_train**: training datasets for common tasks
- **clean_test**: testing datasets for common tasks
- **Completely clean_train, clean_test (Upgraded Version)**: cooming soon
  
## Citation
If you use this dataset in your research, please cite our paper and other related papers:

```bibtex
@article{SUN2026421,
title = {RSMT: Robust stereo matching training with geometric correction, clean pixel selection and loss weighting},
journal = {ISPRS Journal of Photogrammetry and Remote Sensing},
volume = {232},
pages = {421-436},
year = {2026},
issn = {0924-2716},
doi = {https://doi.org/10.1016/j.isprsjprs.2025.12.014},
url = {https://www.sciencedirect.com/science/article/pii/S0924271625004964},
author = {Haoxuan Sun and Taoyang Wang and Qian Cheng and Jiaxuan Huang},
}

```



