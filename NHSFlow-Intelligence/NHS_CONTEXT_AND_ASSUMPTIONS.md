# NHS Context and Assumptions

## 1. What is RTT?
Referral to Treatment (RTT) is the NHS standard that measures 
the time from when a patient is referred by their GP to when 
they start consultant-led treatment. The NHS target is that 
92% of patients should start treatment within 18 weeks of 
referral.

---

## 2. RTT Pathway Types
The NHS England RTT data contains 5 pathway types:

| Code | Description |
|---|---|
| Part_2 | Incomplete pathways — patients still waiting |
| Part_1A | Admitted completed pathways |
| Part_1B | Non-admitted completed pathways |
| Part_2A | Incomplete pathways adjusted |
| Part_3 | New RTT periods starting |

**This project focuses on Part_2 (incomplete pathways)** — 
these are patients currently on the waiting list and have 
not yet started treatment.

---

## 3. The 18-Week Target
- Introduced in 2008 as part of the NHS Constitution
- Requires 92% of incomplete pathway patients to be 
  waiting no longer than 18 weeks
- England has not consistently met this target since 2016
- As of March 2026 only 65.2% of patients are within 
  the 18-week standard

---

## 4. Key Definitions
- **Clock start** — date the referral is received
- **Clock stop** — date treatment begins or pathway ends
- **Breach** — patient waiting longer than 18 weeks
- **Long waiter** — patient waiting longer than 52 weeks
- **Super long waiter** — patient waiting longer than 
  104 weeks (2 years)
- **DNA** — Did Not Attend (missed appointment)

---

## 5. Key Assumptions
- All analysis uses March 2026 data only — single snapshot
- Total waiting list size is calculated by summing all 
  wait band columns as the Total column in source data 
  was not populated
- Breach rate is calculated as patients waiting over 
  18 weeks divided by total waiting
- Private and NHS providers are included in the same 
  analysis but may not be directly comparable due to 
  different case mix
- Commissioner columns contained NaN values for some 
  rows — these were retained but not used in analysis

---

## 6. Data Limitations
- Aggregate data only — no individual patient records
- Single month snapshot — no trend analysis possible
- Some smaller providers report zero activity in certain 
  specialties which is expected and normal
- RTT clock rules are complex — some pathways have 
  clock stops and restarts not captured in this data

---
*NHSFlow Intelligence | NHS Context and Assumptions*