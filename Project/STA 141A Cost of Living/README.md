# U.S. Cost of Living & Affordability Index

This project analyzes the affordability of living in U.S. counties by developing a custom Affordability Index based on normalized living costs and median family income. The work was completed as part of **STA 141A: Fundamentals of Statistical Data Science** at UC Davis.

## Project Summary

- Quantified cost of living using data on housing, food, transportation, healthcare, childcare, taxes, and other necessities.
- Developed an **Affordability Index** by normalizing cost variables and comparing them with median income.
- Created county-level rankings and visualized the distribution of affordability across the U.S.

## Methodology

- **Normalization**: Rescaled all cost-related variables to standardize their influence.
- **Index Formula**:  
  $
  \text{Affordability Index} = \frac{\text{Normalized Income}}{\text{Normalized Total Cost}}
  $
- **Visualization**: Used density plots and scatterplots to show regional patterns and cost/income relationships.
- **Modeling**: Used linear regression to assess the impact of family size on affordability.

## Contents

- `STA_141A_Final_Project.pdf`: Full report including methodology, results, and visualizations.
- `cost_of_living_us.csv`: Dataset used for analysis.
- Source code not included due to academic integrity and course policy. *(Available upon request.)*

## Key Insights

- Childcare, food, and other necessities were the most correlated with total cost.
- Income does not always scale with cost — indicating some regions are significantly more or less affordable.
- The Affordability Index reveals counties where cost burdens are disproportionately high or low.

## Tools Used

- **R**, `ggplot2`, `dplyr`, `lm()` modeling

---

*Created by Zhe Jiang as part of STA 141A coursework at UC Davis.*
