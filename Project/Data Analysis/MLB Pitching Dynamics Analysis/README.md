# Max Fried MLB Pitching Analysis (2017–2021)

This project analyzes the pitching performance of MLB player Max Fried over five seasons (2017–2021). Completed for **STA 160: Practice in Statistical Data Science** at UC Davis, the project utilizes **Statcast data via the pybaseball API** to explore trends in pitch type, speed, spin rate, and strike effectiveness.

## 📌 Project Summary

- Scraped Statcast data on Max Fried from MLB's API using the `pybaseball` library.
- Cleaned and filtered over 10,000 pitches to retain only relevant pitch dynamics.
- Analyzed pitch effectiveness by type, speed, spin rate, and release extension.
- Evaluated trends in **strike rate** over time and across different pitch types.
- Quantified pitch relationships using **correlation** and **mutual information** metrics.

## ⚙️ Methodology

- **Data Collection**: Used `statcast_pitcher` from the [pybaseball](https://github.com/jldbc/pybaseball) package to collect Max Fried's pitching data from 2017–2021.
- **Preprocessing**:
  - Filtered by year and removed deprecated or irrelevant features (e.g. game state, fielder info).
  - Removed pitches marked "in play" (`X`) to reduce uncertainty in pitch outcome classification.
  - Converted categorical `type` to binary (Strike = 1, Ball = 0) for analysis.
- **Feature Engineering**: Added year, grouped pitches by type, and computed strike rates, average speeds, spin rates, and release extensions.
- **Analysis Tools**:
  - Histograms, line plots, and heatmaps for visual EDA.
  - Correlation matrices and mutual information scores to assess predictor relationships.

## 📊 Key Findings

- **Strike rate improved** consistently over the 5-year period, with the highest rate in 2021.
- **Pitch effectiveness varies** by type:
  - Best overall: **Slider (SI)** and **Four-Seam Fastball (FF)**
  - Highest spin: **Curveball (CU)**
  - Best strike rate (2021): **Fastball** at 94+ mph with 0.63 strike rate
- **Effective speed** and **release speed** are highly correlated and strong indicators of pitch success.
- **Release extension** showed minimal impact on pitch outcomes.
- **COVID-shortened 2020 season** showed anomalous performance dips, likely due to smaller sample size.

## 📁 Contents

- `Final Report.pdf`: Full report with EDA, pitch effectiveness analysis, and conclusions.
- Source code not publicly included to comply with academic policy. *(Available upon request.)*

## 🛠️ Tools Used

- **Python**, `pybaseball`, `Pandas`, `Matplotlib`, `Seaborn`, `Sklearn`
- Data Source: [Statcast](https://baseballsavant.mlb.com/) via `pybaseball`

---

*Created by Zhe Jiang as part of STA 160 coursework at UC Davis.*
