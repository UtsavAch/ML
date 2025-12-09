# Breast Cancer Classification

Predicting breast cancer diagnosis (Benign vs Malignant)

## Problem Statement

The goal of this project is to build a machine learning model that predicts whether a breast tumor is **benign** or **malignant** based on clinical features extracted from digitized images of fine needle aspirates of breast masses.

---

## Dataset Overview

This project uses the **Breast Cancer Wisconsin (Diagnostic)** dataset.

- **Total samples:** 569
- **Number of features:** 30
- **Class distribution:**
  - **Malignant:** 212
  - **Benign:** 357

The dataset is known to be **linearly separable** using all 30 features.

---

## Feature Descriptions

Each data point contains 30 numeric features that describe characteristics of cell nuclei present in the image.

Examples include:

- **Radius** – Mean distance from center to perimeter points
- **Texture** – Standard deviation of grayscale values
- **Perimeter**
- **Area**
- **Smoothness** – Local variations in radius lengths
- **Compactness** – \((\text{perimeter}^2 / \text{area}) - 1.0\)
- **Concavity** – Severity of concave regions in the contour
- **Concave Points** – Number of concave regions
- **Symmetry**
- **Fractal Dimension** – “Coastline approximation”

---

## Target Classes

| Label | Description |
| ----- | ----------- |
| 0     | Malignant   |
| 1     | Benign      |

---

## Dataset Source

Breast Cancer Wisconsin (Diagnostic) Dataset  
UCI Machine Learning Repository  
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

---

## Project Goals

- Explore the dataset through visualizations
- Handle missing data
- Train and evaluate classification models (e.g., SVM, KNN)
- Compare performance across different configurations
- Identify the best-performing model

---

## Technologies Used

- Python
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

---
