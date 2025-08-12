# Attention-Based Vision Transformer for Breast Cancer Diagnosis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-1.13+-ee4c2c?logo=pytorch)
![Dataset](https://img.shields.io/badge/Dataset-BreakHis-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Research%20Project-purple)

## 📌 Overview

This repository contains the official implementation of our research paper:

> **Attention-Based Vision Transformers for Enhanced Breast Cancer Diagnosis**  
> *Sana Ullah Khan, Bakht Azam, Hussam Umer*  

In this work, we propose a **self-attention-based Vision Transformer (ViT)** architecture tailored for **multi-class breast cancer histopathology classification** using the **BreakHis dataset**.  
Our model addresses the limitations of traditional CNNs in capturing **long-range dependencies** by leveraging the transformer’s **global context modeling**, achieving:

| Magnification | Accuracy | Precision | Recall | F1-Score |
|---------------|----------|-----------|--------|----------|
| 40X           | 96.25%   | 96.54%    | 96.25% | 96.25%   |
| 100X          | 96.67%   | 96.86%    | 96.67% | 96.66%   |
| 200X          | 96.05%   | 96.11%    | 96.05% | 96.03%   |
| 400X          | 96.25%   | 96.27%    | 96.25% | 96.22%   |
| **Average**   | **96.305%** | **96.305%** | **96.305%** | **96.305%** |

---

## 📂 Dataset

We used the **BreakHis histopathology dataset** containing 7,909 images of benign and malignant tumors across **four magnifications**: 40X, 100X, 200X, and 400X.

**Dataset Preparation:**
- For **each class** at **each magnification level**:
  - **70 images** for training  
  - **30 images** for testing  
- Ensures balanced data for **fair and consistent evaluation**.

---

### 3️⃣ Run notebooks in Google Colab

| Magnification | Colab Link |
|---------------|------------|
| **40X**       | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/BreastCancer-ViT/blob/main/ViT_40X.ipynb) |
| **100X**      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/BreastCancer-ViT/blob/main/ViT_100X.ipynb) |
| **200X**      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/BreastCancer-ViT/blob/main/ViT_200X.ipynb) |
| **400X**      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/BreastCancer-ViT/blob/main/ViT_400X.ipynb) |

