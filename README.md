# HR Attrition Analysis & Interactive Dashboard

## 🚀 Project Overview

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9b58c01d-dd3e-4b96-8d49-21484ce93e56" />



https://github.com/user-attachments/assets/374e3b5d-3049-45ba-b9e7-58b60a903021



This project focuses on a comprehensive **Employee Attrition Analysis** using a synthesized Human Resources dataset. The primary goal is to leverage data analytics and visualization techniques to identify, understand, and predict the key drivers behind employee turnover.

The outcome of this analysis is a structured set of cleaned data and key metrics, designed to power an interactive dashboard (e.g., in Power BI or Tableau) to provide actionable insights for HR and management.

## 📁 Repository Structure and Data Files

This repository is organized to reflect a standard data analysis pipeline, ensuring traceability and clarity from raw data to final analysis output.

| File Name | Role in Project | Description |
| :--- | :--- | :--- |
| `HR Attration Dashboard.xlsx - Raw Data.csv` | **Source Data** | The original, untouched dataset. It contains all initial features and is maintained for auditing and comparison. |
| `HR Attration Dashboard.xlsx - Transformed Data.csv` | **Cleaned & Feature Engineered Data** | The result of the data preparation phase. This file includes clean, validated data suitable for modeling and analysis, along with new features (e.g., `Age Buckets`, `Performance Status`) created for deeper segmentation. |
| `HR Attration Dashboard.xlsx - Analysis.csv` | **Summary & Metrics** | This file holds the final aggregated tables, key performance indicators (KPIs), and calculated metrics derived from the main analysis. It serves as the primary data source for the final visualization/dashboard layer. |

## 📊 Methodology: The Analytical Process

The analysis followed a four-stage process:

1.  **Data Cleaning and Preprocessing:**
    * Handled missing values and standardized data formats.
    * Converted categorical variables (e.g., Job Role, Education Field) into a suitable format for analysis.
    * **Feature Engineering:** Created calculated fields like age bands (`CF_age band`), performance groups, and employee status flags to enhance segmentation capabilities.

2.  **Exploratory Data Analysis (EDA):**
    * Calculated the overall attrition rate.
    * Investigated the relationship between attrition and key demographic factors (**Age, Gender, Marital Status**).
    * Analyzed employee satisfaction metrics (**Job Satisfaction, Environment Satisfaction, Work-Life Balance**) against turnover rates.

3.  **In-Depth Driver Analysis:**
    * Identified high-risk job roles and departments.
    * Explored the impact of compensation-related factors (**Monthly Income, Percent Salary Hike**) and tenure (**Total Working Years, Years At Company**).
    * Used segmentation to isolate the most significant risk groups, informing the data in the `Analysis.csv` file.

4.  **Visualization & Reporting (Implied):**
    * The cleaned data and summary tables were prepared to feed an external tool (like Power BI or Tableau) to build an interactive dashboard, allowing users to drill down into specific factors.

## Key Insights (Example Focus Areas)
* Correlation between job role, monthly income, and attrition.
* Impact of factors like **Job Satisfaction**, **Work-Life Balance**, and **Distance From Home** on employee turnover.
* Demographic analysis (Age, Gender, Marital Status) of employees who left the company.

## 💡 Skills Gained and Demonstrated

| Skill Area | Specific Skills Gained/Demonstrated |
| :--- | :--- |
| **Data Cleaning & Engineering** | Expertise in transforming raw, heterogeneous datasets into clean, structured analytical formats. Demonstrated proficiency in **feature engineering** (creating variables like `CF_age band`, `Performance Status`). |
| **Statistical Analysis (EDA)** | Ability to perform **cohort analysis**, calculate **attrition rates** by segment, and identify significant correlations using measures like mean and distribution. |
| **Business Context & Problem Solving** | Applied analytical thinking to a real-world business problem (employee retention), translating complex data findings into **actionable HR insights**. |
| **Data Storytelling & Reporting** | Structured output data (`Analysis.csv`) specifically for dashboard consumption, ensuring the final visual report is clear, impactful, and easy for non-technical stakeholders to understand. |
| **Project Management** | Successfully managed the entire data lifecycle from ingestion (`Raw Data`) to preparation (`Transformed Data`) to final delivery (`Analysis Data`), showcasing strong organization and pipeline design. |
