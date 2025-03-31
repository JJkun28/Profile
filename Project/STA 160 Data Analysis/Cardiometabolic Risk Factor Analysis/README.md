# Cardiometabolic Risk Factor Analysis

This project investigates the relationships between behavioral, physical, and demographic predictors and three major cardiometabolic diseases: **heart disease**, **stroke**, and **diabetes**. Completed as part of **STA 160: Practice in Statistical Data Science** at UC Davis, the project uses BRFSS survey data and applies information-theoretic techniques to evaluate effective factors at both the population and conditional subpopulation levels.

## 📌 Project Summary

- Explored how health indicators such as **general health**, **BMI**, and **blood pressure** relate to cardiometabolic outcomes.
- Computed **mutual information**, **entropy**, and **odds ratios** to quantify feature importance.
- Analyzed both the **overall population** and **conditional subpopulations** to study how the presence of one disease affects the predictors of another.

## 🧩 Subpopulation Methodology

To isolate the impact of specific health predictors, we defined **conditional subpopulations**:
- For each disease (e.g., diabetes), we created a subpopulation of individuals who had **either stroke or heart disease**, but **not both**.
- This helped us evaluate how predictive factors behave when another cardiometabolic condition is already present — a clinically relevant scenario.
- Example: When studying diabetes, we included only people with stroke or heart disease (but not both), and evaluated how features like BMI or general health changed in predictive strength.

This design allowed for refined comparisons between:
- Mutual information scores in the **overall population** vs. **subgroups**,
- Identifying **consistent predictors** that remain top-ranked across all contexts.

## 🔍 Key Results

- **General health (GenHlth)** consistently ranked as the top predictor across all diseases and populations.
- **BMI** showed **increased importance in subpopulations** for predicting diabetes, suggesting greater influence among patients with existing conditions.
- An interesting case: **CholCheck** showed a high odds ratio with diabetes but **very low mutual information**, meaning frequent cholesterol checks do not necessarily imply causal influence.
- Interaction analysis between **HighBP and HighChol** revealed a **strong ecological effect**, where the combination is more predictive of heart disease than each factor alone.

## 📁 Contents

- `report.pdf`: Final report including full methodology, visualizations, and interpretation.
- `heart_disease_health_indicators_BRFSS2015.csv`: Cleaned dataset used for analysis.
- Source code not publicly included to comply with academic policy. *(Available upon request.)*

## 🛠️ Tools & Techniques

- **Python**, `Pandas`, `Matplotlib`, `Seaborn`, `Sklearn`
- **Mutual Information**, **Conditional Entropy**, **Odds Ratios**, **Ecological Effect Scores**
- Public health dataset: [Kaggle - Heart Disease Health Indicators (BRFSS 2015)](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)

---

*Created by Zhe Jiang as part of STA 160 coursework at UC Davis.*
