# Insurance Charge Regression Analysis

This repository contains the final regression analysis project for **STAT 306 at the University of British Columbia**. The project explores how various demographic and behavioral factors influence insurance charges using a dataset of American insurance customers.

---

## 📌 Project Title
**Exploring the Relationships between Insurance Charges and Multiple Factors: A Regression Analysis**


---

## 🧠 Objectives
- Identify the most significant predictors of insurance charges.
- Build an effective regression model for predicting insurance costs.
- Compare different model selection strategies using metrics like AIC and adjusted R².

---

## 📂 Dataset Overview
- Source: [Kaggle](https://www.kaggle.com/datasets/thedevastator/prediction-of-insurance-charges-using-age-gender)
- Observations: 1338
- Features include:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

---

## 🔍 Analysis Summary
- **Exploratory Data Analysis (EDA):**
  - Visualized relationships using scatter plots, box plots, and a correlation heatmap.
  - Notable finding: Smoking status and BMI have strong correlations with charges.

- **Model Development:**
  - Started with simple linear models (e.g., Age + Smoking).
  - Progressed to include BMI and other categorical variables.
  - Evaluated multiple models using AIC and residual plots.
  - Final model includes:
    - Age, Smoking, BMI, Quadratic BMI term, Number of Children

- **Final Model Performance:**
  - Adjusted R²: ~0.75
  - Lowest AIC across all models tested

---

## ✅ Key Findings
- Smoking status is the most influential predictor of insurance charges.
- Age and BMI also significantly impact charges.
- Region and gender were not statistically significant in our final model.
- A quadratic term for BMI improved model fit, suggesting a nonlinear relationship.

---

## ⚠️ Limitations
- Dataset represents a specific sample and may not generalize.
- External factors like occupation or lifestyle were not included.
- Reliance on AIC may introduce risk of overfitting.

---

## 🚀 Future Work
- Test model performance on external/updated datasets.
- Consider additional features (e.g., exercise level, diet).
- Explore machine learning approaches like Random Forest or Gradient Boosting.
