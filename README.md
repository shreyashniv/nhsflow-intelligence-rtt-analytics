# 🏥 NHSFlow Intelligence
### Real-time RTT Waiting List & Capacity Risk Analytics — NHS England, March 2026

> *7 million patients. 34.8% waiting too long. Which trusts are failing — and why?*

---

## 🔍 What This Project Does
NHSFlow Intelligence turns raw NHS England waiting list data into 
actionable intelligence. Using real RTT data from March 2026, this 
platform identifies which hospital trusts and specialties are under 
the most pressure, flags breach risk, and surfaces the patients who 
have been waiting the longest.

---

## 💡 Key Findings at a Glance

| Metric | Value |
|---|---|
| 🏥 Total patients waiting | 7,045,510 |
| ⚠️ Waiting beyond 18-week target | 2,448,389 (34.8%) |
| 🔴 Waiting over 52 weeks | 95,325 |
| 🚨 Waiting over 2 years | 499 |
| 📊 Worst specialty | Oral Surgery — 44.4% breach rate |
| 🏆 Best performer | Optegra Eye Hospitals — ~0% breach |

---

## 📊 Dashboard Preview
> Power BI dashboard — 6 pages of interactive analysis

| Page | What You'll See |
|---|---|
| Executive Overview | National KPIs at a glance |
| Breach Risk by Specialty | Red/amber/green specialty heatmap |
| Long Waiters | Who has been waiting longest and where |
| Trust Comparison | 477 trusts plotted — size vs breach rate |
| Regional View | Which NHS regions are struggling most |
| Summary & Findings | Key insights and recommendations |

---

## 🛠️ Built With
![Python](https://img.shields.io/badge/Python-3.9-3776AB?logo=python)
![Pandas](https://img.shields.io/badge/pandas-150458?logo=pandas)
![PowerBI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter)

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOURUSERNAME/nhsflow-intelligence-rtt-analytics.git

# Install dependencies
pip install -r requirements.txt

# Run the analysis
jupyter notebook analytics/notebooks/01_eda_waiting_times.ipynb
```

---

## 📁 Project Structure
