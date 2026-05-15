# Machine-Learning-Car-Price-FIFA-Players
End-to-end ML pipeline for car price prediction and FIFA player performance analysis — regression, classification, and ensemble models.

# 🤖 Machine Learning Pipeline — Car Prices & FIFA Players

A comprehensive machine learning project exploring regression and classification tasks across two real-world datasets. The project covers the full ML workflow: from raw data to optimized, production-ready models — with measurable performance improvements across assignments.

---

## 📁 Datasets

| Dataset | Task | Target Variable |
|---------|------|-----------------|
| Car Price Dataset | Regression & Classification | Car selling price |
| FIFA Players Dataset | Regression & Classification | Market value / Performance tier |

---

## 🧪 Models Implemented

### 🚗 Car Price — Regression & Classification
- Linear Regression
- K-Nearest Neighbors (KNN) Classifier

### ⚽ FIFA Players — Regression & Classification
- Polynomial Regression + Ridge & Lasso Regularization
- Logistic Regression + C-sweep Regularization
- Naïve Bayes (Gaussian, Bernoulli, Complement)
- K-Nearest Neighbors (KNN)
- Support Vector Regression (SVR)
- Random Forest Regressor & Classifier
- Gradient Boosting Regressor & Classifier
- Voting & Stacking Ensembles

---

## ⚙️ Techniques & Concepts Covered

- **Feature Engineering** — encoding, scaling, interaction terms, domain-driven feature creation
- **Regularization** — Ridge (L2), Lasso (L1) for regression; C-sweep for logistic regression
- **Cross-Validation (CV)** — K-Fold & Stratified K-Fold for robust, unbiased model evaluation
- **Hyperparameter Optimization** — GridSearchCV to find optimal parameters
- **Learning Curves** — diagnosing underfitting vs. overfitting across model complexity
- **Ensembling** — Voting & Stacking to improve generalization
- **Unified Scouting Pipeline** — end-to-end inference function (value prediction + tier classification)
- **Error Analysis** — R², RMSE, MAE, Accuracy, F1-Score across all models

---

## 📊 Results — Assignment Progression

| Metric | Assignment 2 | Assignment 3 | Improvement |
|--------|-------------|-------------|-------------|
| Best Test R² | 0.1232 | **0.9471** | +0.8239 ✅ |
| Classification Accuracy | 0.8106 | **0.8513** | +0.0407 ✅ |

> The dramatic R² improvement (0.12 → 0.95) reflects the impact of proper feature engineering, regularization, and model selection across the project pipeline.

---

## 📈 Project Goal

Systematically benchmark multiple ML models on each dataset, fine-tune hyperparameters, and improve performance through regularization, feature engineering, cross-validation, and ensemble strategies — ultimately identifying the best model and configuration for each task.

---

## 🗂️ Project Structure

```
├── data/
│   ├── car_price_v3.csv
│   └── Fifa.csv
├── notebook/
│   └── ML_2projects.ipynb
└── README.md
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
