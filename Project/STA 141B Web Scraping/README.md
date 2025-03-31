# NCAA Basketball Web Scraping & Analysis

This project extracts team-level statistics from the NCAA Men's Basketball website using **Selenium WebDriver** and **XPath**. It was completed as part of **STA 141B: Data Technologies for Statistical Analysis** at UC Davis.

## 📌 Project Summary

- Developed a Python scraper using Selenium WebDriver to collect team shooting statistics from the NCAA website for Divisions I–III.
- Extracted 2P, 3P, and FT shot data using **XPath expressions** for precise element targeting.
- Calculated **Points Per Shot (PPS)** and other custom metrics to assess offensive performance.
- Focused on divisional comparisons and an in-depth look at **UC Davis Men's Basketball Team**.

## 🕸️ Web Scraping Details

- Browser automation handled via **Selenium with ChromeDriver**.
- Extracted data by navigating dropdowns and iterating through division-specific pages.
- Used precise **XPath selectors** to target dynamically rendered HTML elements within the page structure.

## 📊 Analysis Highlights

- Division I teams had the highest average PPS, confirming higher offensive efficiency.
- UC Davis showed strong 2-point field goal efficiency but lagged in FT performance.
- Attempted a visual analysis of **team color aesthetics** vs. performance for fun insights.

## 📁 Contents

- `141b_project.pdf`: Final report including scraping process, data processing, and visualizations.
- Source code not publicly included to comply with academic policy. *(Available upon request.)*

## 🛠️ Tools Used

- **Python**, `Selenium`, `XPath`, `Pandas`, `Matplotlib`
- ChromeDriver for browser automation
- Data sourced from [NCAA Men’s Basketball Stats](https://www.ncaa.com/stats/basketball-men)

---

*Created by Zhe Jiang as part of STA 141B coursework at UC Davis.*
