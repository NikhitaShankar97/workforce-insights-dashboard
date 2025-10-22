# Workforce Insights Dashboard (Industry Capstone)

## 📘 Overview
This project was developed as part of the **BADM 550 – Business Analytics Practicum** at the **University of Illinois Urbana-Champaign**, in collaboration with **Colorado West Healthcare System**.  
The goal was to design a **data-driven Workforce Insights Dashboard** to help hospital leadership optimize productivity, monitor turnover, and ensure equitable compensation across departments.

> ⚠️ **Note:** Due to NDA restrictions with the partner organization, the IBM Cognos dashboard and associated datasets cannot be publicly shared. This repository includes only the project presentation and high-level documentation.

---

## 🎯 Business Problem
Colorado West Healthcare faced challenges in:
- Understanding employee productivity and utilization patterns.  
- Identifying turnover hotspots across job families.  
- Ensuring fair and competitive salary distributions for healthcare staff.  

---

## 🔍 Analytics Objectives
1. Develop an **interactive IBM Cognos dashboard** for real-time HR metrics.  
2. Standardize **People Analytics reporting** across departments.  
3. Enable **data-driven workforce planning** and retention strategies.  

---

## 🧩 Data Overview
**Primary Source:** UKG Workforce System  

**Key Data Tables:**
- Employee Information  
- Job History  
- Health Care Eligibility Periods  

**Fields Used:**
- Employee Number, Job Family, Job Family Category  
- Hire Date, Termination Date, Start Date  
- Annual Salary, Hourly Pay Rate  
- Derived Metrics: Productivity %, Turnover %, Active Headcount, Hired vs Terminated counts  

---

## ⚙️ Process
- Extracted and cleaned employee-level data from UKG using **SQL** and **Python**.  
- Built **ETL pipelines** for workforce KPI computation and forecasting.  
- Created **Cognos dashboards** with interactive filters and role-based access.  
- Validated all metrics for accuracy, consistency, and business alignment.  

---

## 📊 Key Insights
- Productivity trends highlighted workload imbalances across job families.  
- Turnover analysis revealed departments with high voluntary attrition.  
- Salary and tenure visualizations supported equitable pay discussions.  
- Automated **labor-cost forecasting (ARIMA)** reduced manual reporting by **10+ hours per week**, improving workforce planning efficiency by **15%**.  

---

## 🛠️ Tools & Technologies
- **IBM Cognos Analytics**  
- **SQL, Python (Pandas, Statsmodels)**  
- **ARIMA Forecasting**  
- **UKG Workforce Data**  
- **Data Visualization & KPI Dashboards**  

---

## 👥 Team & Contributions
Led a **6-member team** responsible for data preparation, metric design, forecasting automation, and dashboard development.  
Collaborated with client stakeholders to align KPIs with organizational priorities and ensure analytical accuracy.  

---

## 📎 File Included
- `/presentation/Workforce_Insights_Dashboard.pptx` – presentation deck 
