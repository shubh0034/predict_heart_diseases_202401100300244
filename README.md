# 🩺 Heart Disease Prediction

This project predicts whether a patient has heart disease based on various medical features using machine learning. It performs classification and evaluates model performance with visual and statistical metrics.

---

## 📌 Problem Statement

**Objective**:  
Predict the presence of heart disease using medical data.  

**Approach**:  
- Use a machine learning classifier (Random Forest)  
- Evaluate using accuracy, precision, recall, F1 score  
- Generate a confusion matrix heatmap

---

## 📂 Dataset

The dataset should be in CSV format. Each row represents a patient's medical records.

**Features:**
- `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`
- `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
- `target` (0 = No Heart Disease, 1 = Heart Disease)

> ⚠️ If your CSV was converted from PDF, this script includes a cleaning function to handle misaligned columns.

---

## 🧠 Model

- **Classifier**: Random Forest
- **Train-Test Split**: 80/20
- **Metrics**:
  - Confusion Matrix (with heatmap)
  - Accuracy :0.85
  - Precision:0.83
  - Recall    :0.88
  - F1 Score  :0.85

---

## ▶️ How to Run

1. Make sure you have Python 3.x installed
2. Install the required packages:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
OUTPUT DISPLAY:-
Accuracy : 0.85
Precision: 0.83
Recall   : 0.88
F1 Score : 0.85
