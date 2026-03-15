# 🇵🇭 Philippine Energy Consumption Analysis (2003–2024)

> *What does 20 years of electricity data tell us about the Philippines? A lot.*

[![Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebook-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/johnpolv/philippine-energy-consumption-analytics)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![DOE](https://img.shields.io/badge/Data-DOE%20Philippines-FFD700?style=for-the-badge)](https://doe.gov.ph)

---

## ⚡ What This Project Is About

The Philippines consumed **126,941 GWh** of electricity in 2024 — nearly **2.4x** more than in 2003. This project digs into *why*, *where*, and *when* that energy is being used, using real government data and Python.

In a country where energy costs directly impact household budgets, business operations, and infrastructure planning — understanding consumption patterns isn't just academic. **It's economic.**

---

## 🔍 The Process

```
📥 Raw PDF (DOE Philippines)
        ↓
🧹 Extracted & structured into 4 clean CSV files
        ↓
🐍 Loaded into Python using Pandas
        ↓
📊 Analyzed: trends · regional · seasonality · energy mix
        ↓
📈 Visualized with Matplotlib (4 charts)
        ↓
💡 Insights written and published on Kaggle & GitHub
```

---

## 🛠️ Tools Used

| Tool | Role |
|------|------|
| **Python + Pandas** | Data cleaning, transformation, and analysis |
| **Matplotlib** | Charts and data visualization |
| **Kaggle** | Notebook development and publishing |
| **GitHub** | Version control and documentation |
| **DOE Philippines** | Official government data source |

---

## 💡 What the Data Revealed

- 📈 **4.3% average annual growth** — demand has nearly doubled in 20 years
- 🏙️ **Luzon accounts for 71%** of national generation — Metro Manila drives the grid
- 🌡️ **May is peak month** — summer heat spikes AC usage nationwide
- ⚠️ **Coal = 62.5% of energy mix** — the country still heavily depends on fossil fuels
- 📉 **2020 saw a −4% dip** — COVID-19 lockdowns visibly impacted national consumption

---

## 🌍 Why This Matters

Energy data is a mirror of economic activity. The findings here have direct implications for:

- **Infrastructure planning** — peak demand months signal where grid upgrades are needed
- **Energy policy** — coal's dominance highlights the urgency of renewable transition
- **Business decisions** — regional consumption gaps reveal where industrial investment is concentrated
- **Household costs** — understanding demand seasonality helps explain why electricity bills spike in summer

This is the kind of analysis that energy regulators, investors, and policymakers rely on — built here from scratch using open data and Python.

---

## 📂 Datasets

All data extracted from **DOE Philippines — 2024 Power Statistics** → [doe.gov.ph](https://doe.gov.ph)

- `yearly_consumption.csv` — 22 years of national consumption by sector
- `regional_generation.csv` — Luzon, Visayas, Mindanao breakdown
- `monthly_consumption_2024.csv` — Month-by-month 2024 data
- `generation_by_plant_type.csv` — Coal, gas, renewables over time

---

## 👤 Author

**Engr. John Paul T. Villaban**
Registered Electrical Engineer | Aspiring Data Analyst

[![Kaggle](https://img.shields.io/badge/Kaggle-johnpolv-20BEFF?style=flat&logo=kaggle)](https://www.kaggle.com/johnpolv)
[![GitHub](https://img.shields.io/badge/GitHub-johnpolv-181717?style=flat&logo=github)](https://github.com/johnpolv)

---

*Data Source: Department of Energy Philippines | doe.gov.ph*
