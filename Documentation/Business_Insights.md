# 🏥 Hospital Emergency Room — Business Insights

## Executive Summary

The Hospital ER dashboard converts **9,216 patient visits** into a management-oriented reporting view using **Excel + Power Query**.

### Current Dashboard KPIs

- **9,216** total patients
- **35.26 minutes** average wait time
- **4.99/10** average patient satisfaction
- **50.04%** admitted
- **49.96%** not admitted
- **59.32%** seen within 30 minutes
- **40.68%** delayed beyond 30 minutes
- **3,816** patients referred

---

## 1. Waiting Time & Service Timeliness

### Finding
Average wait time is **35.26 minutes**. **59.32%** of patients were seen within 30 minutes, while **40.68%** were outside the 30-minute target window.

### Business implication
Waiting-time performance should be monitored against patient volume and peak-hour demand. Staffing, triage flow, and process bottlenecks are potential areas for operational investigation.

---

## 2. Admission Pattern

### Finding
The dashboard shows an almost even admission split:

- **50.04% admitted**
- **49.96% not admitted**

### Business implication
The near 50–50 admission pattern makes patient-flow and capacity planning important. Management can compare admission demand with daily and hourly patient volume.

---

## 3. Patient Satisfaction

### Finding
Average patient satisfaction is **4.99/10**.

### Business implication
Satisfaction should be interpreted together with waiting time and treatment timeliness. Improving service speed may help address patient-experience gaps, although satisfaction can also be influenced by other factors.

---

## 4. Department Referral Workload

### Finding
**3,816 patients** were referred to departments. General Practice is the largest referral category, followed by Orthopedics, Physiotherapy, and Cardiology.

### Business implication
Referral distribution can help management identify departments that require closer workload, staffing, and capacity analysis.

A large **no-referral** segment is also useful for understanding the proportion of ER visits handled without departmental referral.

---

## 5. Patient Demographics

### Finding
The dashboard provides age, gender, and race segmentation. The gender split is approximately **51% male and 49% female**.

### Business implication
Demographic segmentation helps management understand the composition of ER demand and identify patient groups contributing most to overall volume.

---

## 6. Time & Peak-Demand Analysis

### Finding
The dashboard supports year/month filtering and day/hour analysis of patient visits.

### Business implication
Peak-period analysis can support staffing and resource planning by identifying when ER demand is highest.

---

## 7. Analyst Workflow

The project demonstrates a practical analytics pipeline:

`Raw Data → Power Query Transformation → Structured Data → Excel Analysis → KPI Dashboard → Business Insight`

This demonstrates **data preparation + analysis + reporting + interpretation**, rather than dashboard design alone.

---

## 8. Management Questions This Dashboard Can Answer

- How many patients visited the ER?
- What is the average waiting time?
- What percentage are seen within the 30-minute target?
- What percentage of patients are admitted?
- How many patients are referred to departments?
- Which departments receive the highest referral workload?
- How satisfied are patients?
- When are peak patient periods?
- Which demographics contribute most to ER demand?
- Where should management investigate operational bottlenecks?

---

## 9. Portfolio Takeaway

This project demonstrates practical skills relevant to **MIS Executive, Reporting Analyst, Data Analyst, Operations Analyst, and Business Analyst** roles.

The strongest part of the project is the combination of **Power Query data transformation + Excel dashboarding + KPI analysis + operational business interpretation**.
