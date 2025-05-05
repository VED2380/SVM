# 🎯 Breast Cancer Detection using SVM

A clean and simple ML project that uses Support Vector Machines (SVM) to classify breast cancer tumors as **benign** or **malignant** using extracted features.

---

## 📂 Project Structure

```
Dataset used
├  ├──breast-cancer .csv  # 🎲 Dataset
├
├── cancer_svm.ipynb       # 📘 Main notebook for training/testing
├── svm.ipynb              # 🧪 Experiments with different kernels
└── README.md              # 📄 Project description
```

---

## 📊 Dataset Description

- **File**: `breast_cancer.csv`
- **Entries**: 569 samples
- **Target column**: `diagnosis`  
  - `0` = benign, `1` = malignant
- **Features**: 30 numerical columns including:
  - `radius_mean`, `texture_mean`, `area_worst`, `smoothness_se`, etc.
- **Missing values**: None
- **Shape**: `(569, 31)`

---

## 🔧 Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib (optional for visualization)
- jupyter (to run notebooks)

---

## 🧠 Model Overview

- Classifier: **Support Vector Machine (SVM)**
- Kernels used: `linear`, `rbf`, etc.
- Preprocessing: Label encoding, feature scaling
- Evaluation: Accuracy, confusion matrix

---
