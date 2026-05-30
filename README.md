# Hospital Readmission & Complexity Optimization
### End-to-End Clinical Analytics | SQL · Microsoft Power BI · Healthcare BI

---

## 📋 Project Overview

An independent end-to-end healthcare analytics project built on a real-world 
clinical dataset of 32,202 patient encounters. The goal was to audit the data, 
identify operational bottlenecks, and deliver an executive-grade Power BI 
reporting model that translates raw clinical data into actionable business intelligence.

---

## 🏥 Business Problem

Hospital readmissions are one of the most costly and preventable challenges 
in modern healthcare systems. This project set out to answer three questions:

- What is the scale of the readmission problem in this patient population?
- Which patient cohorts are driving the highest operational burden?
- What does the data tell us about average care complexity and length of stay?

---

## 🗃️ Dataset

| Property | Detail |
|---|---|
| Total Records | 32,202 patient encounters |
| Source Type | Healthcare transactional database |
| Anomalies Removed | 80 malformed rows (0.24% anomaly rate) |
| Cleaning Tool | SQL |
| Final Clean Dataset | 32,122 validated patient encounters |

---

## 🔧 Technical Methodology

### Phase 1 — Data Auditing & Cleaning (SQL)
- Imported raw transactional dataset and performed full schema validation
- Identified and excluded 80 malformed rows via SQL filtering
- Applied type casting and null value auditing across all critical fields
- Validated referential integrity across patient encounter records
- Exported clean dataset for downstream BI modeling

### Phase 2 — Analytical Modeling (Power BI)
- Connected validated dataset to Power BI Desktop
- Built a relational data model with appropriate field relationships
- Developed DAX measures for KPI calculations
- Applied visual hierarchy principles to executive dashboard layout
- Implemented color-grading on highest-volume cohorts for immediate insight visibility

---

## 📊 Key Findings

| Metric | Value | Clinical Significance |
|---|---|---|
| Average Length of Stay | 15.01 days | Indicates exceptionally complex clinical baseline |
| 30-Day Readmission Rate | 50% | Critical threshold — major intervention target |
| Peak Complexity Cohort | 2,222 patients | Presenting with 14 distinct co-morbid diagnoses |
| Data Anomaly Rate | 0.24% | 80 rows excluded for calculation integrity |

---

## 🚨 Critical Insight

A **50% thirty-day readmission rate** was identified across the patient population.

This is a severe operational and clinical signal. In well-functioning health systems, 
readmission rates above 15-20% trigger mandatory review. A 50% rate indicates 
systemic issues in discharge planning, post-acute care coordination, or patient 
complexity management that require immediate executive attention.

Combined with a 15.01-day average length of stay and a peak cohort of 2,222 patients 
carrying 14 co-morbidities simultaneously, this dataset tells a clear story: 
this patient population is extraordinarily complex and the system is not currently 
equipped to manage that complexity at discharge.

---

## 📈 Executive Dashboard

The final deliverable was a production-grade Power BI executive reporting model featuring:

- KPI cards for core metrics (readmission rate, average length of stay, patient volume)
- Bar chart with color-graded highest-volume cohort in deep dark blue for immediate visibility
- Visual hierarchy designed for C-suite and clinical leadership consumption
- Clean, professional layout optimised for executive decision-making

> 📎 *Executive PDF report available in this repository*

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| SQL | Data cleaning, schema validation, anomaly exclusion |
| Microsoft Power BI Desktop | Data modeling, DAX measures, dashboard design |
| Power Query | Data transformation and loading |
| Microsoft Excel | Preliminary data inspection |

---

## 💡 Domain Context

This project was built with biochemistry and clinical domain knowledge informing 
the analytical approach. Understanding what a 50% readmission rate means 
clinically — not just statistically — is what separates a technically correct 
analysis from a genuinely useful one.

---

## 👤 Author

**Ramazon Anzhirov**  
Healthcare BI Specialist | SQL · Power BI · Clinical Data Analytics  
📍 Dubai, UAE · Open to Global Remote  
🔗 [LinkedIn](https://www.linkedin.com/in/ramazon-a-839980403/) · [GitHub](https://github.com/rzanjirov3)
