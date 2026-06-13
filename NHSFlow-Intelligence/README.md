# NHSFlow Intelligence
### RTT Waiting List and Capacity Risk Analytics Platform

![NHS](https://img.shields.io/badge/Data-NHS%20England%20Open%20Data-005EB8)
![Python](https://img.shields.io/badge/Python-3.9-blue)
![PowerBI](https://img.shields.io/badge/Dashboard-Power%20BI-F2C811)
![Status](https://img.shields.io/badge/Status-Complete-009639)

---

## Project Purpose
NHSFlow Intelligence is an end-to-end analytics platform built on 
real NHS England RTT data to monitor waiting list pressure, identify 
breach risk, and support operational decision-making across hospital 
trusts and specialties in England.

---

## Key Findings
- 🏥 **7 million patients** on the NHS waiting list as of March 2026
- ⚠️ **34.8% (2.4 million)** waiting beyond the 18-week RTT target
- 🔴 **95,325 patients** have waited over 52 weeks
- 🚨 **499 patients** have waited over 2 years
- 📊 **Trauma & Orthopaedic** has the largest backlog — 826,000 patients
- 📈 **Oral Surgery** has the worst breach rate at 44.4%

---

## Dashboard
The Power BI dashboard contains 6 pages:

| Page | Description |
|---|---|
| Executive Overview | National KPIs and specialty breach summary |
| Breach Risk by Specialty | Breach rates with red/amber/green classification |
| Long Waiters | 52+ and 104+ week waiter analysis |
| Trust Comparison | Scatter plot and table of 477 trusts |
| Regional View | Breach rates by NHS region |
| Summary and Findings | Key findings and recommendations |

---

## Data Source
All data is sourced from NHS England open data. No patient-level 
or identifiable data is used.

- **Source:** NHS England RTT Waiting Times — March 2026
- **URL:** https://www.england.nhs.uk/statistics/statistical-work-areas/rtt-waiting-times
- **Scope:** 532 providers, 24 specialties, England-wide
- **Pathway:** Incomplete pathways (Part 2) — active waiting list only

---

## Project Structure