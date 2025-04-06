# Occupational Risk of Byssinosis in Cotton Textile Workers

This project investigates the relationship between workplace exposure and the respiratory disease **byssinosis** using real-world health and employment data. It was completed as part of **STA 138: Introduction to Biostatistics** at UC Davis.

## 📌 Project Summary

- Analyzed data from a 1973 study of over 5,400 textile workers in North Carolina.
- Examined how factors such as **workplace dustiness**, **smoking**, **employment duration**, **sex**, and **race** relate to the presence of byssinosis.
- Built and evaluated **logistic regression models** to identify significant predictors of the disease.

## 🔧 Methodology

- **Exploratory Data Analysis**: Summarized disease prevalence across predictor levels and visualized relationships.
- **Model Selection**: Used **forward stepwise logistic regression** guided by AIC and BIC to choose relevant predictors.
- **Hypothesis Testing**: Conducted a likelihood ratio test to confirm workplace dustiness as a significant factor.
- **Interpretation**: Analyzed coefficients to understand risk factors and interactions (e.g., smoking & dust exposure).

## 📁 Contents

- `Final Project.pdf`: Full report detailing analysis, model selection, and interpretations.
- Source code not included due to academic integrity and course policy. *(Available upon request.)*

## 📊 Analysis Insights

- **Workplace dustiness** is strongly associated with the likelihood of developing byssinosis.
- **Smoking** and **longer employment duration** significantly increase disease risk.
- Interaction effect: smokers in less dusty environments showed slightly different patterns than expected.
- Variables like **sex** and **race** had minimal influence on disease prevalence.

## 🛠️ Tools Used

- **R**, `glm()`, stepwise AIC/BIC selection, visualizations using base plotting and diagnostic checks

---

*Created by Ka Yan Tang, Zhe Jiang, Caitlyn Koyabu, and Adrayene Swartzendruber for STA 138 at UC Davis.*
