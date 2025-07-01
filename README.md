# 🩺 Insurance Cost Prediction using Machine Learning

This project predicts individual medical insurance charges using personal and lifestyle data. It applies and compares the performance of **Linear Regression** and **Random Forest Regressor**.

---

## 📂 Dataset

- **Source**: [Kaggle – Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Features**:
  - `age`: Age of the insured person
  - `sex`: Gender (male/female)
  - `bmi`: Body Mass Index
  - `children`: Number of children covered by insurance
  - `smoker`: Smoking status
  - `region`: Region in the U.S.
  - `charges`: Medical insurance cost (target variable)

---

## 🧠 ML Models Used

| Model              | Description                                              |
|-------------------|----------------------------------------------------------|
| Linear Regression  | Simple baseline regression assuming linearity           |
| Random Forest      | Ensemble-based model handling non-linear relationships  |

---

## 🔁 Workflow

1. Data Loading & Cleaning
2. Categorical Feature Encoding
3. Train-Test Splitting
4. Model Training
5. Model Evaluation using R² Score
6. Custom Cost Prediction

---

## 📈 Results (Example)

| Metric        | Linear Regression | Random Forest |
|---------------|-------------------|----------------|
| R² (Train)    | 0.75              | 0.97           |
| R² (Test)     | 0.74              | 0.83           |

✅ Random Forest outperformed Linear Regression with better generalization.

---

## 📊 Visualizations


- Distribution plots for features
- Model performance comparison
- 

---

## 🚀 Getting Started

### 📦 Requirements

Install all necessary Python packages:

### bash

pip install pandas numpy matplotlib seaborn scikit-learn xgboost
