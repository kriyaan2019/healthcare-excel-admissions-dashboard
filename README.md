# healthcare-excel-admissions-dashboard
Excel-based healthcare admissions dashboard analyzing patient volume, length of stay, readmissions, and charges using formulas, pivots, and interactive slicers.


## Project Overview
This project analyzes healthcare admissions data to monitor operational performance across hospital departments. Using Microsoft Excel, I built an interactive dashboard that tracks patient volume, length of stay (LOS), readmissions, and financial impact, helping stakeholders quickly identify areas for improvement.

The project demonstrates **data analysis**: data cleaning, KPI calculation, pivot analysis, and dashboard storytelling.


## Business Problem
Healthcare administrators need clear visibility into:
- Admission volume by department
- Average length of stay compared to departmental targets
- Readmission rates
- Financial impact of patient care



##  Tools Used
- **Microsoft Excel**
  - Formulas: COUNTIFS, SUMIFS, AVERAGE, IF, XLOOKUP
  - Data cleaning: TRIM, UPPER, SUBSTITUTE
  - Pivot Tables & Charts
  - Slicers for interactivity
  - Dashboard design & formatting



##  Dataset
- Synthetic (fake) healthcare admissions data created for portfolio purposes
- ~240 patient records (Jan–Mar 2024)
- Includes realistic data quality issues:
  - Missing discharge dates (patients still admitted)
  - Missing charges (billing not finalized)
  - Inconsistent department text formatting

**Key Fields:**
- Patient_ID, Age, Gender
- Department, Admission_Date, Discharge_Date
- Length_of_Stay (calculated)
- Readmitted (Yes/No)
- Total_Charges


##  Data Cleaning & Preparation
To ensure accurate analysis:
- Standardized department names using `TRIM`, `UPPER`, and `SUBSTITUTE`
- Created calculated LOS from admission and discharge dates
- Preserved missing clinical/financial values instead of imputing them
- Used helper columns to keep raw data immutable

## 📈Key KPIs
- **Total Admissions**
- **Average Length of Stay**
- **Readmission Rate**
- **Total Charges**
- **% of Stays Above Department LOS Target**

All KPIs were built using **formulas (not hardcoded values)** to ensure transparency and auditability.


## Dashboard Features
- Executive-style Excel dashboard
- KPI cards for quick performance review
- Department-level comparison of admissions and LOS
- Monthly admissions trend analysis
- Interactive slicers (Department, Gender)
- Clear separation of raw data, analysis, and presentation layers


## Key Insights
- Emergency Room has the shortest LOS but the highest admission volume
- Cardiology and Neurology frequently exceed LOS targets
- Readmission rate (22%) indicates opportunities for improved post-discharge follow-up
- LOS above target correlates with higher operational strain


##  Recommendations
- Review discharge workflows in high-LOS departments
- Expand post-discharge care programs to reduce readmissions

- Use this dashboard weekly to monitor LOS vs targets
- Prioritize interventions in departments with repeated over-target stays

- ##  How This Project Can Be Extended
- Automate monthly refresh using Power Query
- Add provider-level or diagnosis-level analysis
- Connect to SQL database for larger datasets
- Build a Tableau or Power BI version for enterprise deployment


## Author
**Krishna Mishra**  
Aspiring Healthcare Data Analyst  
Skills: Excel | SQL | Data Analysis | Healthcare Operations


*This project was completed as part of my professional portfolio to demonstrate real-world data analytics skills.*

<img width="468" height="249" alt="image" src="https://github.com/user-attachments/assets/d1ef755a-9013-4f7d-bde0-b8680a9d5ce0" />

