# 🧠 Brain Tumor Detection using Swin-B Transformer

## Overview
This project focuses on detecting brain tumors from MRI scans using the **Swin-B Transformer**, a vision transformer architecture that captures both **local** 🔍 and **global** 🌍 image features.  
The objective was to build a **robust deep learning model** capable of classifying MRI scans into **tumor** 🩻 and **non-tumor** ✅ categories.

## Our Solution
We designed and trained a Swin-B Transformer on preprocessed MRI datasets with data augmentation techniques, including **thermal augmentation** 🌡️, to enhance feature extraction.  
After **100 epochs**, the model achieved:  
- **Training Accuracy:** ~100%  
- **Validation Accuracy:** **91.18%**

## Key Highlights
- Preprocessed MRI images, including resizing, normalization, and augmentation.  
- Implemented the **Swin-B Transformer** for accurate classification.  
- Achieved **91.18% validation accuracy**, demonstrating strong generalization.  
- Future improvements:  
  - Expanding dataset diversity.  
  - Optimizing model robustness.  
  - Enhancing interpretability using techniques like Grad-CAM or attention visualization.

## Dataset
MRI brain scans (tumor & non-tumor) sourced from:  [Brain MRI Images for Brain Tumor Detection - Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)  
Kaggle Notebook: [Work on Kaggle](https://www.kaggle.com/code/hsn123345/brain-tumor-detection-using-swinb)

## Gratitude
Thanks to the open-source community, mentors, and researchers for inspiration.  
