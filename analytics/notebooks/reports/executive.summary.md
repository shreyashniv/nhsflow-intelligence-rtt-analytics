# NHSFlow Intelligence — Executive Summary
## RTT Waiting List and Capacity Risk Analytics
**Data Source:** NHS England RTT Waiting Times — March 2026  
**Author:** [Your Name] | MSc Data Science and Analytics  
**Date:** June 2026

---

## 1. Project Purpose
This project analyses the NHS England Referral to Treatment (RTT) 
waiting list to identify breach risk, long waiters, and performance 
variation across hospital trusts and specialties. The aim is to 
support operational decision-making by surfacing where capacity 
pressure is most acute and where intervention is most needed.

---

## 2. Data
- **Source:** NHS England Open Data — RTT Waiting Times March 2026
- **Scope:** 532 hospital providers, 24 specialties, England-wide
- **Records:** 183,400 rows — aggregate waiting time bands by 
  trust, specialty, and pathway type
- **Pathway focus:** Incomplete pathways (Part 2) — patients 
  currently waiting for treatment

---

## 3. Key Findings

### Finding 1 — Scale of the Problem
As of March 2026, **7,045,510 patients** are on the NHS waiting 
list in England. This represents a significant ongoing pressure 
on the health system following post-Covid recovery efforts.

### Finding 2 — 18-Week Target Breach
**2,448,389 patients (34.8%)** are waiting beyond the 18-week 
RTT standard. The NHS target is that 92% of patients should 
start treatment within 18 weeks — the current position is 
significantly below this standard.

### Finding 3 — Long Waiters
**95,325 patients** have been waiting over 52 weeks — more than 
a year. Of these, **499 patients** have waited over 104 weeks 
(2 years), representing the most serious performance failures 
in the system.

### Finding 4 — Specialty Variation
Breach rates vary significantly by specialty:
- **Oral Surgery** — 44.4% breach rate (highest)
- **Plastic Surgery** — 43.4% breach rate
- **Trauma and Orthopaedic** — 40.9% breach rate but largest 
  raw backlog at 826,000 patients
- **Elderly Medicine** — 17.2% breach rate (best performing)

### Finding 5 — Provider Type Variation
Private sector providers show disproportionately high breach 
rates. Pioneer Healthcare (88.5%), Spire Southampton (76.1%), 
and Nuffield Health Wessex (71.8%) all exceed 70% breach rate. 
In contrast, specialist eye providers such as Optegra operate 
at near 0% breach rate.

---

## 4. Recommendations

1. **Prioritise Trauma and Orthopaedic capacity** — with 826,000 
   patients and 19,000 waiting over 52 weeks this specialty 
   requires urgent theatre and consultant capacity investment.

2. **Review private sector contracts** — breach rates exceeding 
   70-88% in independent sector providers suggest contract 
   performance management needs strengthening.

3. **Target Oral Surgery and ENT** — both specialties combine 
   high breach rates with large list sizes making them priority 
   areas for demand management and capacity planning.

4. **Implement long waiter watchlists** — the 499 patients 
   waiting over 2 years require immediate clinical review and 
   escalation to ensure no further deterioration.

5. **Learn from high performers** — Optegra's near-zero breach 
   rate demonstrates that focused, high-volume care pathways 
   can consistently meet the 18-week standard. This model 
   should be studied and applied where possible.

---

## 5. Limitations
- Single month snapshot (March 2026) — no trend analysis possible
- Aggregate data only — no patient-level analysis
- Private and NHS providers not directly comparable due to 
  different case mix and contract structures
- RTT clock rules vary by pathway type — some comparisons 
  may not be fully like-for-like

---

## 6. Tools and Methods
- **Python** — data loading, cleaning, transformation, 
  exploratory analysis
- **pandas / numpy** — data manipulation
- **matplotlib / seaborn** — analytical charts
- **SQLite** — data warehouse
- **Power BI** — interactive dashboard

---
*NHSFlow Intelligence | MSc Data Science and Analytics Portfolio*