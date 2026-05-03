# Healthcare Analytics – Power BI Dashboard Project

> **A Business Analyst portfolio project** exploring patient outcomes, hospital performance, billing patterns, and department efficiency using a synthetic healthcare dataset and Power BI.

---

## Project Overview

This project simulates a real-world healthcare analytics scenario where a Business Analyst is tasked with building an executive-level Power BI dashboard for a multi-region hospital network. The goal is to surface actionable insights around patient demographics, treatment costs, readmission rates, and departmental performance.

| Item | Detail |
|------|--------|
| **Domain** | Healthcare / Hospital Operations |
| **Tool** | Microsoft Power BI Desktop |
| **Dataset** | Synthetic (100 patient records, Jan–Sep 2024) |
| **Rows** | 100 patients |
| **Columns** | 20 fields |

---



---

## Dataset Description

The dataset (`healthcare_analytics_dataset.csv`) contains **100 patient records** across **20 columns**, covering admissions from January to September 2024 across four US regions.

### Column Reference

| Column | Type | Description |
|--------|------|-------------|
| `Patient_ID` | Text | Unique patient identifier |
| `Age` | Integer | Patient age in years |
| `Gender` | Text | Male / Female |
| `Blood_Type` | Text | ABO blood group |
| `Admission_Date` | Date | Hospital admission date |
| `Discharge_Date` | Date | Hospital discharge date |
| `Department` | Text | Hospital department (e.g., Cardiology, Oncology) |
| `Diagnosis` | Text | Primary diagnosis |
| `Procedure` | Text | Treatment or procedure performed |
| `Length_of_Stay_Days` | Integer | Days between admission and discharge |
| `Total_Bill_USD` | Decimal | Total hospital bill in USD |
| `Insurance_Provider` | Text | Insurance company name |
| `Insurance_Coverage_Percent` | Integer | % of bill covered by insurance |
| `Out_of_Pocket_USD` | Decimal | Patient's out-of-pocket expense |
| `Doctor_ID` | Text | Attending physician ID |
| `Satisfaction_Score` | Integer | Patient satisfaction (1–5 scale) |
| `Readmission_30Days` | Text | Yes/No – readmitted within 30 days |
| `Region` | Text | Hospital region (North, South, East, West) |
| `Bed_Type` | Text | ICU / Private / General |
| `Emergency_Admission` | Text | Yes/No – emergency admission flag |

---

##  Key Business Questions Answered

1. **Which departments generate the highest revenue and longest stays?**
2. **What is the 30-day readmission rate by department and region?**
3. **How do insurance providers differ in coverage and patient out-of-pocket costs?**
4. **What is the average patient satisfaction score by doctor and department?**
5. **How does age group affect diagnosis complexity, billing, and length of stay?**
6. **What proportion of admissions are emergency vs. planned?**
7. **Which regions have the highest ICU utilisation?**

---

## Dashboard Pages (Power BI)

The Power BI report contains **4 dashboard pages**:

### Page 1 – Executive Summary
- KPI cards: Total Patients, Avg Bill, Avg Stay, Readmission Rate
- Monthly admission trend (line chart)
- Patient distribution by Region (donut chart)
- Emergency vs. Planned admissions (stacked bar)

### Page 2 – Department & Clinical Analysis
- Revenue by Department (bar chart)
- Avg Length of Stay by Department (horizontal bar)
- Top 10 Diagnoses by frequency (bar chart)
- Bed type utilisation (treemap)

### Page 3 – Financial & Insurance Analysis
- Total Billing vs. Out-of-Pocket by Insurance Provider (clustered bar)
- Insurance Coverage % comparison (gauge or bar)
- Revenue heatmap by Region × Department (matrix)
- Avg Bill by Age Group (column chart)

### Page 4 – Patient Outcomes & Satisfaction
- Readmission rate by Department (bar chart)
- Satisfaction Score distribution (histogram)
- Satisfaction vs. Length of Stay (scatter plot)
- Readmission rate by Region (map visual)

---

## Tools & Technologies

- **Microsoft Power BI Desktop** (free download)
- **Microsoft Excel / CSV** for data source
- **DAX** for calculated measures
- **Power Query** for data transformation

---



---

## Key Insights (Sample Findings)

- **Cardiology and Oncology** account for ~55% of total hospital revenue
- **30-day readmission rate** is highest in the Oncology and Neurology departments
- **Medicare patients** have the highest coverage (90%) but also the highest total bills
- **Emergency admissions** tend to have 2× longer average stays than planned admissions
- **Patient satisfaction** is inversely correlated with length of stay in ICU beds

---


**[M]**  
Business Analyst | Data & Healthcare Analytics Enthusiast  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

---

