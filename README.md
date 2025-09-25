# Raisin Classification with Logistic Regression

This repository contains my assignment on the **Raisin Dataset**, where I trained and evaluated a Logistic Regression model using **Python (pandas, NumPy, scikit-learn)** in Google Colab.

## 📊 Dataset
- The dataset used is **Raisin_Dataset.xlsx**, which contains two types of raisins:
  - **Besni (0)**
  - **Kecimen (1)**

## 🛠️ Steps in the Notebook
1. Imported required libraries (pandas, NumPy, scikit-learn).
2. Mounted Google Drive and loaded the dataset.
3. Preprocessed the data:
   - Dropped the target column (`Class`) from features.
   - Encoded labels: Besni → 0, Kecimen → 1.
4. Split the dataset into **80% training** and **20% testing** (with stratification).
5. Trained a **Logistic Regression model**.
6. Evaluated performance using:
   - Accuracy
   - Classification report
   - Confusion matrix
   - **5-fold cross-validation**

## ✅ Results
- Test Accuracy: ~ (fill in your actual accuracy here, e.g. `0.82`)
- Mean CV Accuracy: ~ (fill in your CV mean score here)

## 🚀 Tools & Environment
- Google Colab
- Python 3
- Libraries: pandas, NumPy, scikit-learn

---

📌 This assignment demonstrates the use of Logistic Regression and model evaluation with cross-validation.
