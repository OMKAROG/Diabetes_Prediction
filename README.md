# Diabetes Prediction using Logistic Regression and Ensemble Techniques

## 📌 Overview
This project implements a machine learning model for predicting diabetes based on diagnostic medical data. The work is inspired by the research paper:

"Prediction of diabetes using logistic regression and ensemble techniques" :contentReference[oaicite:0]{index=0}

The goal is to improve prediction accuracy using:
- Logistic Regression
- Feature Selection
- Support vector machines
- Ensemble Methods (Max Voting, Stacking)

---

## 🚀 Features
- Data preprocessing (handling missing & zero values)
- Feature engineering (custom features based on medical insights)
- Feature selection (Univariate Chi-Square)
- Logistic Regression model
- Ensemble techniques:
  - Majority Voting
  - Stacking
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## 📂 Datasets Used
1. **PIMA Indians Diabetes Dataset**
2. **Vanderbilt Diabetes Dataset**

---

## ⚙️ Workflow
1. Load dataset
2. Data exploration (correlation, distributions)
3. Data preprocessing (handling missing values)
4. Train-test split (70:30)
5. Model training using Logistic Regression
6. Apply feature selection techniques
7. Apply ensemble methods
8. Evaluate performance

---

## 🧠 Techniques Used

### 🔹 Logistic Regression
- Base model for classification
- Probabilistic prediction

### 🔹 Feature Selection
- Custom feature engineering
- Univariate feature selection (Chi-square)

### 🔹 Ensemble Methods
- **Max Voting**: Combines predictions from multiple models
- **Stacking**: Uses multiple base models + meta-model

---

## 📊 Results

| Method | Dataset 1 Accuracy | Dataset 2 Accuracy |
|--------|------------------|------------------|
| Logistic Regression | 74% | 88% |
| Feature Selection | 75% | 89% |
| Max Voting | 77% | 93% |
| Stacking | 76% | 93% |

---

## 🛠️ Tech Stack
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn



# Run notebook/script
python main.py
