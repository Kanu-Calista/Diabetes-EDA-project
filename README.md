# DIABETES EDA PROJECT

## Overview

This project performs an in-depth exploratory data analysis (EDA) on Diabetes dataset to uncover insights and visualize key trends. The dataset contains information on the age, glucose levels, BMI, bloodpressure and their outcome.

## Libraries & Tool

- Python 
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook 

---

## 🔍 Objectives

- Understand the structure and quality of the dataset.
- Explore distributions, correlations, and outliers.
- Identify patterns and meaningful relationships.
- Prepare a clean dataset for further modeling or decision making.

---

## 📊 Key Visualizations & Insights

### 1. Age Distribution



- Most individuals fall within the **25–40** age range.
- There is a noticeable drop-off in participants over 60 years old.

---

### 2. BMI Category Distribution



- The majority of individuals fall into the **Overweight** and **Obese** categories.
- Only a small fraction are **Underweight**, suggesting a greater concern for high BMI-related health risks.
- This trend may indicate potential lifestyle or dietary patterns in the population sampled.
  
---

### 3. Blood Pressure Category Distribution



No significant difference in blood pressure between diabetic and non-diabetic individuals, though outliers exist in both groups

---

### 4. Correlation Heatmap



- **BMI** and **Glucose** show strong positive correlation with diabetes outcome.
- **Age** has a moderate correlation with **Glucose** and **BMI**, Indicating increased risk with age.

---

## Key Findings

- The dataset is skewed towards younger adults.
- There are health risk patterns related to weight, gender, and age.
- Certain variables (e.g., blood pressure, BMI) show clear correlations worth exploring for predictive modeling.

---

## Next Steps

- Feature engineering and scaling
- Predictive modeling (classification of health risks)
- Dashboarding with Streamlit or Power BI

---

## Note

All charts were generated in Python and exported to the `/images/` directory for easy rendering in this README.
