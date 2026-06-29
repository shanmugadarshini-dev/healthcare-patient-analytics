# Healthcare Revenue & Patient Analytics
### 55,500 Patient Records | 2019–2024 | Excel Dashboard

## Business Problem
A multi-specialty hospital needed to understand revenue 
patterns, billing anomalies, length-of-stay efficiency, 
and clinical test outcomes across 55,500 patient records 
spanning 6 years.

## Tools Used
Microsoft Excel — Pivot Tables, Power Query, 
Conditional Formatting, Charts, Slicers, KPI Cards

## Dataset
55,500 patient records | 15 fields including:
Admission type, Medical condition, Insurance provider, 
Billing amount, Medications, Test results, LOS (calculated)

## Key Findings

1. BILLING ANOMALY — Cancer patients averaged ₹25,161 
   billing vs ₹25,805 for Obesity — despite significantly 
   higher clinical complexity. Potential underbilling 
   of ₹46–116 lakh annually.

2. DATA INTEGRITY — 108 records contained negative 
   billing amounts across all 6 conditions, indicating 
   a billing system error requiring immediate audit.

3. LOS EFFICIENCY — Average length of stay was 15.5 days 
   across ALL admission types (elective, urgent, emergency). 
   Elective LOS should be 3–5 days per industry benchmark — 
   the hospital is running at 3x, blocking 55,000+ 
   bed-days per year unnecessarily.

4. ABNORMAL TEST RATE — Arthritis had the highest 
   abnormal test result rate (34.3%) but second-lowest 
   avg billing — a billing capture gap worth ₹X in 
   missed charges.

5. PARTIAL YEAR FLAG — 2024 data is incomplete. 
   Dashboard includes a partial-year label to prevent 
   stakeholder misinterpretation.

## Dashboard Features
- 5 KPI cards (Total Revenue, Patients, Avg LOS, 
  Emergency Admissions, Top Insurer)
- 6 interactive slicers
- 5 chart types
- Billing anomaly flag

## Business Recommendations
1. Audit oncology billing codes — estimate ₹116L 
   recoverable revenue
2. Introduce condition-specific discharge protocols 
   for elective patients
3. Add billing validation rule to catch negative 
   amounts before month-end close

## What I Would Add With More Time
- Month-over-month revenue trend with partial year fix
- Readmission rate analysis by condition
- Cost per bed-day calculation
- Insurance claim denial rate by provider
