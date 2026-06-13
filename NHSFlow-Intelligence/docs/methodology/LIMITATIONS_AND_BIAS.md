# Limitations and Bias

## 1. Data Limitations

### Single Month Snapshot
This analysis uses March 2026 data only. No trend analysis 
is possible — we cannot determine whether waiting lists are 
growing or shrinking, or whether breach rates are improving 
or worsening over time. A more complete analysis would use 
12-24 months of data to identify seasonal patterns and 
directional trends.

### Aggregate Data Only
The NHS England RTT dataset is aggregate — it shows counts 
of patients in each wait band by trust and specialty, not 
individual patient records. This means we cannot:
- Track individual patient journeys
- Identify specific at-risk patients
- Analyse demographic factors such as age, ethnicity, 
  or deprivation
- Calculate precise median waiting times per patient

### Total Column Not Populated
The Total column in the source data was not populated for 
all rows. Total waiting list size was recalculated by 
summing all wait band columns. This approach is valid but 
may introduce small discrepancies compared to official 
published totals.

---

## 2. Analytical Limitations

### Breach Rate Calculation
Breach rate is calculated as patients waiting over 18 weeks 
divided by total patients waiting. This is a point-in-time 
measure and does not account for:
- Patients who were treated and removed from the list
- Patients who were referred but not yet booked
- Clock stops and restarts within pathways

### Single Metric Focus
This analysis focuses primarily on waiting time as the key 
performance metric. Other important dimensions not captured 
include:
- Clinical urgency and priority
- Patient outcomes after treatment
- Cost of care
- Staff capacity and workforce data

---

## 3. Bias Considerations

### Private vs NHS Provider Comparison
Private sector providers such as Spire, Nuffield, and Pioneer 
Healthcare are included in the same analysis as NHS trusts. 
This comparison may not be fully like-for-like because:
- Private providers typically treat lower complexity cases
- Case mix differs significantly from NHS trusts
- Contract structures and reporting requirements differ
- Some private providers only treat specific specialties

High breach rates in private providers may reflect case mix 
or contract issues rather than genuine performance failure.

### Specialty Case Mix
Breach rates across specialties are not directly comparable 
because:
- Some specialties treat more urgent conditions and 
  therefore see patients faster
- Surgical specialties require theatre access which is 
  a shared constrained resource
- Mental Health RTT rules differ from physical health

### Geographic Bias
Regional analysis uses provider parent organisation as a 
proxy for geography. This does not perfectly reflect 
patient geography as patients may travel across regions 
for treatment.

---

## 4. Recommendations for Future Analysis
- Obtain 12+ months of RTT data for trend analysis
- Link to patient-level data where available under 
  appropriate governance
- Include workforce and capacity data to contextualise 
  breach rates
- Add deprivation and demographic data to identify 
  equity issues
- Build predictive models using historical trends to 
  forecast future breach risk

---
*NHSFlow Intelligence | Limitations and Bias*