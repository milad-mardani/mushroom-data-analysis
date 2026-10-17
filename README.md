# 🍄 Mushroom Classification & Feature Importance Analysis

## 📌 Project Overview

This project explores the characteristics of edible and poisonous mushrooms using data cleaning, statistical analysis, feature importance evaluation, machine learning classification, and Power BI visualization.

Developed as part of my Data Analysis training, the project investigates which mushroom attributes are most useful for distinguishing edible mushrooms from poisonous ones.

The project uses the UCI Mushroom Dataset and combines statistical methods, machine learning techniques, and data visualization to explore patterns in categorical data.

## 🎯 Project Objectives

- Clean and prepare the dataset for analysis.
- Explore relationships between mushroom characteristics and edibility.
- Identify important features using statistical and machine learning techniques.
- Compare feature importance across different analytical approaches.
- Apply machine learning classification algorithms.
- Present analytical findings through a three-page Power BI dashboard.
- Document feature importance findings and comparisons.

## 🔄 Project Workflow

### 1. Data Cleaning & Preparation

Prepared the dataset for analysis by examining data quality, handling missing-value indicators, and checking data consistency.

Key activities:
- Inspecting the dataset structure.
- Handling missing or invalid values.
- Preparing categorical features for further analysis.

### 2. Statistical Analysis & Feature Importance

Applied statistical methods to investigate the relationships between mushroom attributes and the target class.

**Statistical Methods**

- **Chi-Square Test:** Examined associations between categorical mushroom features and edibility.
- **Cramér's V:** Measured the strength of association between categorical variables.

**Explainable AI (XAI) & Feature Importance**

- **SHAP (SHapley Additive exPlanations):** Analyzed feature contributions to model predictions.
- **Permutation Importance:** Evaluated the effect of permuting individual features on model performance.

**Feature Representation**

- Label-based feature representation.
- One-hot encoding for categorical features.

These approaches provide complementary perspectives on feature relevance. Statistical association does not necessarily imply causation, and feature importance may vary across models and evaluation methods.

### 3. Machine Learning Classification

Applied machine learning classification algorithms to explore patterns associated with edible and poisonous mushrooms.

The project includes K-Nearest Neighbors (KNN) and other classification experiments.

This stage focuses on learning patterns from mushroom characteristics and evaluating their usefulness for classification.

### 4. Power BI Dashboard

Developed a Power BI dashboard consisting of three pages to visualize the analysis and communicate key findings.

The dashboard complements the Python-based analysis by providing a visual overview of mushroom characteristics and analytical results.

### 5. Findings & Documentation

Created a Word document summarizing important features and their rankings across the feature importance analysis.

This documentation helps organize the analytical findings and compare the insights obtained from different methods.

## 🛠️ Technologies & Methods

**Programming & Data Analysis**
- Python
- Pandas
- NumPy
- Jupyter Notebook

**Statistical Analysis**
- Chi-Square Test
- Cramér's V

**Machine Learning**
- Scikit-learn
- Classification algorithms
- Feature importance analysis

**Explainable AI (XAI)**
- SHAP
- Permutation Importance

**Data Visualization**
- Matplotlib
- Seaborn
- Microsoft Power BI

## 📂 Repository Contents

The repository is intended to contain the following project files. File names should match the actual uploaded files.

- `DataCleaning.ipynb` — Data cleaning and preparation.
- `FeatureImportant_Label.ipynb` — Feature importance analysis using label-based features.
- `FeatureImportant_one.ipynb` — Feature analysis using one-hot encoding.
- `ML.ipynb` — Machine learning classification experiments.
- `Summary of Feature.docx` — Summary of feature importance findings.
- `mushroom_analysis.pbix` — Power BI dashboard containing three pages of visualizations.

## 📈 Key Learning Outcomes

This project provided practical experience in:

- Data cleaning and preparation.
- Exploratory data analysis.
- Statistical analysis of categorical variables.
- Feature encoding and feature importance evaluation.
- Machine learning classification.
- Explainable AI techniques.
- Power BI dashboard development.
- Communicating analytical findings through documentation and visualization.

## 👨‍💻 Author

**Milad Mardani**

- **GitHub:** [milad-mardani](https://github.com/milad-mardani)
- **LinkedIn:** [Milad Mardani](https://www.linkedin.com/in/miladmardani/)

## ⚠️ Disclaimer

This project is intended for educational and analytical purposes only. Its findings and classification models must not be used to determine whether real mushrooms are safe to eat.
