# Brain Tumor Classification Using Deep Learning

## Overview
This repository presents a deep learning–based system for **multi-class brain tumor classification** using MRI images. The model accurately categorizes brain scans into four clinically relevant classes and is evaluated using robust statistical metrics to ensure strong generalization and reliability.

**Classes:**
- Glioma Tumor  
- Meningioma Tumor  
- Pituitary Tumor  
- Normal (No Tumor)

---

## Dataset
- **Type:** Brain MRI images  
- **Task:** Multi-class image classification  
- **Number of Classes:** 4  
- **Preprocessing:**
  - Image resizing and normalization
  - Train–validation–test split
  - Optional data augmentation

---

## Model Architecture
- Deep learning–based vision model (CNN / Transformer-based backbone)
- Transfer learning used for feature extraction
- Fully connected classification head
- Softmax activation for multi-class prediction

---

## Training Details
- **Loss Function:** Categorical Cross-Entropy  
- **Optimizer:** Adam / AdamW  
- **Evaluation Strategy:** One-vs-Rest (OvR) multi-class evaluation  
- **Regularization:** Data augmentation and early stopping (if enabled)

---

## Performance Evaluation

### ROC Curve (AUC)
| Class | AUC |
|------|-----|
| Glioma Tumor | 0.99 |
| Meningioma Tumor | 0.99 |
| Normal | 1.00 |
| Pituitary Tumor | 1.00 |

The ROC curves indicate excellent class separability across all categories.

---

### Precision–Recall Curve (Average Precision)
| Class | AP |
|------|----|
| Glioma Tumor | 0.98 |
| Meningioma Tumor | 0.97 |
| Normal | 1.00 |
| Pituitary Tumor | 0.99 |

High Average Precision values demonstrate strong reliability, particularly for tumor detection.

---


## Visual Results
The repository includes:
- Multi-class ROC curves
- Multi-class Precision–Recall curves

These visualizations support transparent and interpretable model evaluation.

---

## Applications
- Computer-aided diagnosis (CAD)
- Medical image analysis research
- Clinical decision support systems
- Benchmarking multi-class classification models

---

## Requirements
- Python 3.x
- TensorFlow or PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- OpenCV / PIL

---


