# Africa Disease Burden Analysis (2000–2021)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![matplotlib](https://img.shields.io/badge/matplotlib-3.7-orange) ![WHO](https://img.shields.io/badge/Data-WHO%20GHO%20API-orange) ![Africa](https://img.shields.io/badge/Focus-47%20Countries-green)

**Analysis of life expectancy and child mortality across 47 African countries using live WHO data — with Ghana deep dive, West Africa regional comparison, and 20-year progress tracking.**

> Author: Afriyie Karikari Bempah, PharmD | [LinkedIn](https://linkedin.com/in/afriyiekarikaribempah) | [GitHub](https://github.com/akbempah1)

---

## Overview

This project uses the WHO Global Health Observatory API to analyze two decades of health progress across Africa. It explores country-level life expectancy and child mortality trends, identifies the continent's fastest-improving health systems, and provides a Ghana-specific deep dive with West African regional context.

> **Data note:** WHO GHO health statistics currently available to 2021. A 2–3 year publication lag is standard due to country reporting cycles and cross-country data validation requirements.

---

## Key Findings

| Finding | Implication |
|---|---|
| **23-year life expectancy gap within Africa** | Algeria/Mauritius at 75+ vs CAR at 52 — same continent, vastly different health systems |
| **Rwanda gained 20.6 years in 21 years** | Community health workers + UHC = transformative population health impact |
| **Ghana gained 7 years, cut child mortality 60%** | NHIS and primary healthcare expansion measurably visible in data |
| **HIV/AIDS treatment scale-up visible in data** | Zimbabwe, Malawi, Zambia show sharp life expectancy upturns post-2005 |
| **Child mortality strongly predicts life expectancy** | Investing in child survival has outsized population health returns |
| **Ghana ranks top in West Africa** | Regional model for health system strengthening |

---

## Visualizations

1. **Life expectancy trends** — Top 5 and bottom 5 countries side by side (2000–2021)
2. **Country rankings** — All 47 African countries color-coded by life expectancy band
3. **Ghana deep dive** — Life expectancy trend, under-5 mortality trend, West Africa comparison
4. **Scatter plot** — Life expectancy vs child mortality, all countries (2021)
5. **Top improvers** — Top 15 countries by life expectancy gained (2000–2021)

---

## Skills Demonstrated

- Live API data retrieval and JSON parsing (WHO GHO)
- Multi-indicator data merging and deduplication
- Matplotlib multi-panel visualizations
- Country-level public health storytelling
- Regional benchmarking and comparative analysis

---

## How to Run

```bash
git clone https://github.com/akbempah1/africa-disease-burden-analysis.git
pip install pandas numpy matplotlib requests jupyter
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

*Data sourced from WHO Global Health Observatory. Analysis and interpretations are independent and not affiliated with WHO.*
