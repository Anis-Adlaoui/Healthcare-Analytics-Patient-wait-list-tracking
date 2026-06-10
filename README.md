# 🏥 Healthcare Patient Waiting List Analytics

## 📌 Project Overview
End-to-end Power BI dashboard analyzing patient waiting lists 
in the Irish healthcare system (2018–2021), covering Inpatient, 
Outpatient, and Day Case categories.

## 🎯 Business Objectives
- Track the **current status** of the patient waiting list
- Analyze **historical monthly trends** across Inpatient & Outpatient
- Enable **specialty-level and age profile** deep-dive analysis

## ❓ Questions This Dashboard Answers

**Overview**
- What is the current total number of patients on the waiting list?
- How does the current waitlist compare to the same period last year?

**Trends**
- How has the waiting list evolved month over month between 2018 and 2021?
- Is the waitlist growing faster for Inpatients or Outpatients over time?

**Specialty & Demographics**
- Which medical specialties have the highest patient backlog?
- What age groups are waiting the longest?
- How are patients distributed across time bands (0–3 months, 3–6 months, 18+ months...)?

**Interactivity**
- Is the average or median a better representation of wait times for a given specialty?
- How does the picture change when filtering by case type or time period?

## 💡 Decision Making & Actionable Insights

- Redirect surgical staff and beds toward specialties with the highest and fastest-growing backlogs
- Prioritize funding for units where 18+ month waitlist bands are expanding
- Use monthly trend data to forecast future demand and plan hiring or infrastructure ahead of peak periods
- Flag age groups consistently sitting in the longest time bands for targeted intervention
- Benchmark performance year-over-year to measure impact of healthcare reforms or budget changes

## 📊 Dashboard Pages
| Page | Description |
|------|-------------|
| Summary | KPI cards, donut chart, trend lines, toggle Avg/Median |
| Detailed View | Matrix drill-down by specialty, age, time band |

## 🛠️ Tech Stack & Skills
- **Power BI Desktop** — report development
- **Power Query (M)** — data transformation, append, cleaning
- **DAX** — calculated measures (SWITCH, EDATE, CALCULATE...)
- **Data Modelling** — star schema, specialty mapping table
- **Design** — custom background (Canva/PowerPoint), tooltips, navigation


## 📂 Data Source
Public (https://pivotalstats.com/end-end-power-bi-dashboard-development/)
Scope: 2018–2021 | Granularity: Monthly
