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
- Applied type casting and null value auditing a
