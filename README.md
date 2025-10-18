# 🩺 UCI Heart Disease Prediction using K-Nearest Neighbors (KNN)

This project uses the **K-Nearest Neighbors (KNN)** algorithm to predict the likelihood of heart disease based on the **UCI Heart Disease Dataset**. The workflow includes data loading, preprocessing, feature scaling, model training, and evaluation.

---

## 📂 Dataset

The dataset is from the **UCI Heart Disease dataset**:

- **Path (Kaggle Notebook):** `/kaggle/input/uci-dataset/heart_disease_uci.csv`
- **Number of features:** 13 clinical attributes
- **Target column:** `target` (1 = disease, 0 = no disease)
- **Features include:**
  - Age
  - Sex
  - Chest Pain Type (cp)
  - Resting Blood Pressure (trestbps)
  - Serum Cholesterol (chol)
  - Fasting Blood Sugar (fbs)
  - Resting ECG results (restecg)
  - Maximum Heart Rate Achieved (thalach)
  - Exercise Induced Angina (exang)
  - Oldpeak
  - Slope
  - Number of major vessels (ca)
  - Thal

---

## 🧰 Requirements

Install the required Python libraries:

```bash
pip install pandas scikit-learn
