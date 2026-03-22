# Africa Disease Burden Analysis — Interactive Dashboard (2000–2021)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Plotly](https://img.shields.io/badge/Plotly-interactive-green) ![WHO](https://img.shields.io/badge/Data-WHO%20GHO%20API-orange) ![Africa](https://img.shields.io/badge/Focus-Africa-red)

**Interactive analysis of life expectancy and child mortality across 47 African countries using live WHO data — with Ghana deep dive and 20-year progress tracking.**

> Author: Afriyie Karikari Bempah, PharmD | [LinkedIn](https://linkedin.com/in/afriyiekarikaribempah) | [GitHub](https://github.com/akbempah1)

---

## Overview

This project uses the WHO Global Health Observatory API to analyze two decades of health progress across Africa. Interactive Plotly visualizations allow exploration of country-level trends, regional patterns, and Ghana-specific health system performance.

---

## Key Findings

| Finding | Implication |
|---|---|
| **23-year life expectancy gap within Africa** | Algeria/Mauritius at 75+ vs CAR at 52 — same continent, vastly different health systems |
| **Rwanda gained 20.6 years in 21 years** | Community health workers + UHC = transformative population health impact |
| **Ghana gained 7 years, cut child mortality 60%** | NHIS and primary healthcare expansion are measurably visible in the data |
| **HIV/AIDS treatment scale-up visible in data** | Zimbabwe, Malawi, Zambia show sharp life expectancy upturns post-2005 |
| **Child mortality strongly predicts life expectancy** | Investing in child survival has outsized population health returns |

---

## Visualizations

1. **Line chart** — Life expectancy trends for top 5 and bottom 5 countries (2000–2021)
2. **Choropleth map** — Life expectancy across all 47 African countries (2021)
3. **Ghana deep dive** — Life expectancy + under-5 mortality trends (2000–2021)
4. **Scatter plot** — Life expectancy vs child mortality, all countries (2021)
5. **Bar chart** — Top 15 countries by life expectancy improvement

---

## New Skills in This Project

- Plotly Express for interactive charts
- Plotly Graph Objects for custom subplots
- Choropleth map visualization
- Multi-indicator WHO API data integration
- Country-level public health storytelling

---

## How to Run

```bash
git clone https://github.com/akbempah1/africa-disease-burden-analysis.git
pip install pandas numpy matplotlib plotly requests jupyter
jupyter notebook africa_disease_burden.ipynb
```

No API key required. All data pulled live from WHO GHO API.

---

## Portfolio Series

- [Project 1 — Medicare Drug Spending](https://github.com/akbempah1/medicare-drug-spending-analysis)
- [Project 2 — FDA Adverse Events](https://github.com/akbempah1/fda-adverse-events-analysis)
- [Project 3 — Hospital Readmissions](https://github.com/akbempah1/hospital-readmissions-prediction)
- [Project 4 — Pharma Portfolio](https://github.com/akbempah1/pharma-stock-portfolio-analysis)
- [Project 5 — Credit Risk Scoring](https://github.com/akbempah1/credit-risk-scoring)
- **Project 6 — Africa Disease Burden** ← you are here

---

*Data sourced from WHO Global Health Observatory. Analysis and interpretations are independent.*
