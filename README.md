# Ensemble CNN Fusion for Precise Brain Tumor Detection and Classification

This repository contains the source code and models for a deep learning-based approach to detect and classify brain tumors using MRI images. The ensemble model integrates ResNet-50, VGG-16, and MobileNet architectures to enhance detection accuracy. The project aims to provide an efficient and accurate solution for early diagnosis of brain tumors, leveraging the strengths of different CNN architectures.

## Table of Contents
- [Project Overview](#project-overview)
- [Models Used](#models-used)
- [Dataset](#dataset)
- [Results](#results)
- [Contributors](#contributors)

## Project Overview

Brain tumors are a major health concern worldwide. Early and accurate detection is essential for improving patient outcomes. This project uses an ensemble of convolutional neural networks (CNNs) for classifying brain tumors from MRI images into four categories:
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The ensemble model combines the strengths of three CNN architectures—ResNet-50, VGG-16, and MobileNet—to achieve a high classification accuracy of **99.7%**. The goal is to provide an advanced method for detecting brain tumors, aiding clinicians in making more informed decisions.

## Models Used

### 1. ResNet-50
- Architecture: 50 layers deep
- Strengths: Efficient in capturing complex features, particularly useful for brain MRI analysis.

### 2. VGG-16
- Architecture: 16 convolutional layers
- Strengths: Known for strong feature extraction capabilities.

### 3. MobileNet-V2
- Architecture: Lightweight, optimized for mobile and embedded devices.
- Strengths: Efficient in terms of speed and performance, ideal for real-time analysis.

### Ensemble Model
The ensemble model fuses the outputs of the above networks to provide superior classification results.

## Dataset

The dataset used for this project is a combination of publicly available MRI brain tumor datasets. It includes:
- **Glioma**: 1621 images
- **Meningioma**: 1645 images
- **Pituitary Tumor**: 1757 images
- **No Tumor**: 2000 images

Images are resized to 150x150 pixels, pre-processed, and normalized for training.

## Results

The ensemble model achieved the following performance metrics:
- **Accuracy**: 99.7%
- **Precision**: 99.9%
- **Recall**: 99.8%
- **F1-Score**: 99.9%

The **ROC curve** demonstrates perfect classification with an AUC of 1.0 for all four classes.

## Contributors

- Challa Anudeep Reddy
- Katta Santhosh Kumar Reddy
- Kolli Tushar
