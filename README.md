# Payroll-Intelligence-Risk-Monitoring-Dashboard
📌 Project Overview

This project is an end-to-end Payroll Analytics and Risk Detection solution built using Power BI. The goal of the project is to identify salary leakage, overtime abuse, and ghost employees by transforming raw payroll data into actionable executive-level insights.

The project simulates a real-world corporate payroll environment and demonstrates skills in data cleaning, Power Query transformations, DAX KPI creation, and executive dashboard design.
![Payroll & Attendance Dashboard](dashboard%20overview.png)


🎯 Objectives

Detect salary leakage in payroll processing

Identify overtime abuse beyond policy limits

Flag ghost employees (inactive or zero-attendance employees receiving salary)

Provide executive-level insights for payroll governance and audit teams

🗂 Dataset Information

Dataset Name: Payroll_Dataset

Records: 100+ synthetic employee payroll records

Dataset Type: Self-created (synthetic)

File Format: CSV

Key Fields Included

Employee ID & Name

Department

Employment Status (Active / Inactive)

Base Salary

Overtime Hours

Attendance Days

Overtime Cost

Total Pay

Payroll Risk Flags

🧹 Data Cleaning & Transformation (Power Query)

All data preparation was performed using Power Query Editor in Power BI.

Steps Performed:

Removed duplicate employee records

Handled missing and invalid values

Corrected data types (salary, overtime, attendance)

Standardized department and status names

Created calculated columns:

Overtime Cost

Total Pay

Salary Leakage Flag

Ghost Employee Flag

Filtered inconsistent payroll entries

📊 KPIs & Metrics (DAX)

Key KPIs were created using DAX measures to support risk detection:

Total Payroll Cost

Total Overtime Cost

Average Salary

Salary Leakage Amount

Overtime Abuse Count

Ghost Employee Count

Payroll Exception Rate

High-Risk Employee Count

These KPIs power all visuals in the dashboard.

📈 Dashboard Design

🔹 Section 1: Executive KPI Summary

KPI Cards showing overall payroll health

🔹 Section 2: Salary Leakage Analysis

Department-wise salary leakage visuals

🔹 Section 3: Overtime Abuse Monitoring

Overtime hours vs threshold analysis

🔹 Section 4: Ghost Employee Detection

Identification of inactive or zero-attendance paid employees

🔹 Section 5: Department Risk Analysis (Compulsory)

Risk concentration across departments

🔹 Section 6: Employee-Level Drill-Down (Compulsory)

Detailed employee-wise payroll risk table

🧠 Key Insights

Overtime abuse is a major contributor to salary leakage

Ghost employees indicate gaps in HR–Payroll reconciliation

Payroll risks are concentrated in specific departments

Targeted audits can significantly reduce payroll losses

✅ Business Recommendations

Automate payroll validation rules

Implement strict overtime approval workflows

Conduct monthly payroll audits

Integrate HR, attendance, and payroll systems

Use dashboards for proactive risk monitoring

🛠 Tools & Technologies

Power BI – Data visualization & dashboarding

Power Query – Data cleaning & transformation

DAX – KPI & measure creation

Microsoft Excel – Initial dataset validation

📄 Project Deliverables

Power BI Dashboard (.pbix)

Cleaned Payroll Dataset (.csv)

KPI Definitions Document

Executive Insight Report

GitHub README (this file)

🎓 Learning Outcomes

Hands-on experience with real-world payroll analytics

Strong understanding of Power Query and DAX

Ability to design executive-level dashboards

Experience in risk detection and business storytelling
