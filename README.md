# Medical_Insurance_cost_prediction

# 🩺 Insurance Cost Prediction using Machine Learning

This project predicts individual medical insurance costs using personal and lifestyle information. We explore and compare two models: **Linear Regression** and **Random Forest Regressor**.

---

## 📂 Dataset

- **Source**: [Kaggle – Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Features**:
  - `age`: Age of the insured person
  - `sex`: Gender (male/female)
  - `bmi`: Body Mass Index
  - `children`: Number of children covered by insurance
  - `smoker`: Whether the person smokes
  - `region`: Region in the U.S.
  - `charges`: Insurance cost (target variable)

---

## 🧠 ML Models Used

| Model              | Description                                              |
|-------------------|----------------------------------------------------------|
| Linear Regression  | A simple baseline regression model assuming linearity   |
| Random Forest      | An ensemble-based model that handles non-linearity well |

---

## 🔁 Workflow

1. Data Loading & Exploration
2. Data Preprocessing (encoding categorical columns)
3. Train-Test Split (80-20)
4. Model Training (Linear & Random Forest)
5. Model Evaluation (R² score)
6. Cost Prediction on New Input

---

## 📈 Results (Sample)

| Metric        | Linear Regression | Random Forest |
|---------------|-------------------|----------------|
| R² (Train)    | 0.75              | 0.97           |
| R² (Test)     | 0.73              | 0.91           |

✅ **Random Forest** showed significantly better performance on test data.

---

## 📊 Visualizations

- Correlation heatmap
- Feature distribution plots
- Actual vs Predicted scatter plots
- Model performance comparison bar chart

---

## 🚀 Getting Started

### Requirements
Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
