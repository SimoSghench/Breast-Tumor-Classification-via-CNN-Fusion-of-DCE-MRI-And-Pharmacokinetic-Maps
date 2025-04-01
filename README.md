# Breast Tumor Classification via CNN Fusion of DCE-MRI & Pharmacokinetic Maps

## Overview
This project presents a deep learning framework for classifying breast tumors by combining Dynamic Contrast-Enhanced MRI (DCE-MRI) data with pharmacokinetic maps derived from the Extended Tofts Model (ETM). By leveraging convolutional neural networks (CNNs) and fusion architectures, the framework improves the accuracy of molecular subtype classification in breast cancer diagnostics.

## Motivation
Breast cancer is a leading cause of cancer-related mortality. Early and accurate subtype classification is crucial for effective treatment. This project addresses imaging challenges by:
- **Integrating Multi-Modal Data:** Combining contrast-enhanced MRI with quantitative pharmacokinetic maps.
- **Advanced Deep Learning:** Utilizing EfficientNet-B3 and fusion strategies to enhance feature representation.
- **Robust Evaluation:** Applying comprehensive experimental setups and statistical tests to validate model performance.

## Features
- **Data Preprocessing:** Automated conversion of raw DICOM images into 4D volumes, ROI extraction, and 2D slice generation.
- **Pharmacokinetic Mapping:** Generation of voxel-wise parameter maps (Ktrans, ve, vp) using the Extended Tofts Model.
- **CNN Architectures:** Implementation of DCE-only, ETM-only, and dual-modality models with intermediate and late fusion strategies.
- **Evaluation Metrics:** Detailed performance analysis using accuracy, precision, recall, F1-score, and AUC with bootstrap confidence intervals.
