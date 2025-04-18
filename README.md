# Salary Prediction with Machine Learning 📊

This project explores how machine learning regression models can predict a person's salary based on their years of professional experience. Built as the final assignment for the ITAI 2377 course at Houston Community College.

---

## 📁 Project Structure

```
salary-prediction-ml-final/
├── data/
│   └── Salary_dataset.csv
├── notebooks/
│   └── DS_WED_21229_FINALEXAM_SolorzanoNatalia_ITAI2377.ipynb
├── reports/
│   ├── DS_WED_21229_FINALEXAM_SolorzanoNatalia_ITAI2377.pdf
│   └── comparison_table.csv
├── requirements.txt
└── README.md

```

---

## 🧪 Dataset

- Source: [Kaggle - Salary Dataset](https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression)
- Columns: `YearsExperience`, `Salary`

---

## 🔧 Preprocessing Steps

- Duplicate and outlier removal (Z-score)
- Salary log transformation (to reduce skew)
- Polynomial feature generation (`YearsExperience^2`)
- StandardScaler for feature normalization
- Data split: 70% Train, 15% Validation, 15% Test

---

## 🤖 Models Trained

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- K-Nearest Neighbors Regressor
- Voting Regressor Ensemble (optional: Bayesian Ensemble)

Metrics evaluated: **MAE**, **MSE**, **R²**

---

## 🏆 Best Model

- **Linear Regression** outperformed others with an R² of 0.80 on the validation set.
- Ensemble Voting Regressor tested for performance stability on unseen data.

---

## 🚀 How to Run

1. Clone the repository  
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook:
    ```
    jupyter notebook notebooks/DS_WED_21229_FINALEXAM_SolorzanoNatalia_ITAI2377.ipynb
    ```

---

## 📎 Author

**Natalia Solorzano Perez**  
W207818526 – Spring 2025  
Solo project submitted for ITAI 2377: Data Science in AI  
Houston Community College
