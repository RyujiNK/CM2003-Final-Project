# CM2003-Final-Project


# Odelia Breast MRI Challenge – ResNet50 Model

**Authors:** Joakim Brandt Öberg & Natthaphong Kaewkam

**Date:** November 2025

---

## Overview
This project was developed as part of the **Odelia Breast MRI Challenge**, with the goal of building a deep learning model to assist in the early and accurate detection of breast cancer.  
The approach uses a **ResNet50** convolutional neural network to classify MRI studies into three categories: *no lesion*, *benign*, and *malignant*.

---

## Methodology
The model was implemented using **PyTorch** and trained on a dataset of **256 MRI studies**, which presented a significant class imbalance (mostly “no lesion” cases).  

**Key techniques:**
- Transfer learning with a pretrained **ResNet50** backbone  
- **Dropout layers** (0.5 and 0.4) to reduce overfitting  
- **Cosine annealing learning rate scheduling** for smoother convergence  
- **Class weighting** in the loss function to handle dataset imbalance



