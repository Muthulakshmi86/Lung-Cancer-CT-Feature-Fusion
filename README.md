# Lung-Cancer-CT-Feature-Fusion
Implementation of a Tri-Fusion deep learning framework for lung cancer classification from CT images.
# Lung Cancer CT Classification using Tri-Fusion Deep Learning

This repository contains the implementation code and trained models for the research work on automated lung cancer classification from computed tomography (CT) images using a Tri-Fusion feature learning framework.

## Overview
The study investigates the effectiveness of feature-level fusion by combining deep features extracted from multiple convolutional neural network backbones for robust lung cancer classification. The proposed Tri-Fusion approach integrates complementary representations to improve classification performance.

## Dataset
The original CT images are obtained from the publicly available **IQ-OTHNCCD Lung Cancer Dataset**:
[IQ-OTHNCCD Lung Cancer Augmented Dataset](https://www.kaggle.com/datasets/aleksandarcvetanov/iq-othnccd-lung-cancer-augmented-dataset)

Raw CT images are **not redistributed** in this repository in accordance with dataset ownership and repository policies.

## Data Availability
The minimal reproducibility dataset required to replicate the results reported in the manuscript, including patient-wise train/validation/test splits, preprocessing details, and extracted feature representations, is archived on **Figshare**:

**DOI:** [Reproducibility Dataset on Figshare](https://doi.org/10.6084/m9.figshare.31278340)

## Repository Contents
- `scripts/` – Training and evaluation scripts  
- `models/` – Trained model weights (where applicable)  
- `features/` – Extracted deep feature representations  
- `utils/` – Utility functions and preprocessing helpers  

## Methodology
- CT image preprocessing 
- Deep feature extraction using CNN backbones  
- Feature-level fusion (Tri-Fusion)  
- Classification using deep learning classifiers  
- Evaluation using accuracy, precision, recall, and F1-score  

## Reproducibility
To reproduce the results:
1. Download the IQ-OTHNCCD dataset from the original source.
2. Obtain the reproducibility data from Figshare using the provided DOI.
3. Apply the patient-wise split indices and preprocessing steps.
4. Run the training and evaluation scripts provided in this repository.

## License
This code is released under the **MIT License**, allowing reuse with appropriate attribution.

## Citation
If you use this work, please cite the corresponding manuscript.
