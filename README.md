<img width="1448" height="1086" alt="ae5dde51-9f91-4714-8aed-0013695d4dc3" src="https://github.com/user-attachments/assets/bf42800e-3ddf-4d4d-941c-7cecc23648e0" />End-to-end data analysis of a real-world healthcare dataset — from raw data to actionable business insights using Python, SQL, and Power BI.


📊 Dashboard Preview

![Uploading ae5dde51-9f91-4714-8aed-0013695d4dc3.png…]() 

Note: Open Healthcare dashboard.pbit in Power BI Desktop to explore the full interactive dashboard.




📌 Project Overview

This project explores a healthcare dataset to uncover patterns in patient demographics, medical conditions, hospital billing, and operational performance — with the goal of generating insights that could support clinical and administrative decision-making.

The full pipeline covers data cleaning, exploratory analysis, SQL-based querying, and a Power BI dashboard.


🎯 Business Questions Answered


What are the most common medical conditions across patient demographics?
How do billing amounts vary by condition, age group, and hospital?
What is the average length of stay — and what factors influence it?
Are there seasonal patterns in hospital admissions?
Which patient segments carry the highest risk or cost?
What correlations exist between test results, conditions, and billing?



🔍 Analysis Performed

AnalysisDescriptionDemographic EDAAge, gender, blood type distribution across the datasetMedical Condition TrendsFrequency and severity analysis by condition typePatient Risk SegmentationGrouping patients by risk level based on test resultsLength of Stay AnalysisFactors influencing hospital stay durationBilling & Revenue PatternsCost breakdown by condition, age, and insuranceSeasonal Admission TrendsMonthly and quarterly admission pattern analysisSQL Window FunctionsRanking, running totals, and cumulative billing analysisCorrelation AnalysisStatistical relationships between key clinical variables


🛠️ Tools & Technologies

ToolUsagePythonCore analysis languagePandas & NumPyData wrangling and numerical computationMatplotlib & SeabornVisualization and EDA chartsSQL + SQLite/PostgreSQLAdvanced querying, CTEs, window functionsPower BIInteractive dashboard (.pbit template)Jupyter NotebookDevelopment and documentation environment


📂 Repository Structure

healthcare-analysis/
├── healthcare_analysis.ipynb   # Main analysis notebook
├── healthcare_dataset.csv      # Dataset used for analysis
├── Healthcare dashboard.pbit   # Power BI dashboard template
├── mydatabase.db               # SQLite database
└── README.md


💡 Key Insights


💡 Key Insights


51–60 is the highest-volume age group (8,297 patients). The 10–20 bracket has the lowest count (2,443) — younger individuals have significantly lower hospital dependency.
Gender split is near-perfect 50/50 (Male 50.04% / Female 49.96%). No medical condition shows a strong gender preference — Arthritis has the largest gap at just 64 patients.
Admission type drives length of stay more than medical condition. Cancer Emergency averages 19.67 days vs Cancer Urgent at 11.85 days — a 7-day difference purely from admission type. Age has virtually zero correlation with stay duration (r = 0.0038).
Billing is remarkably uniform across all conditions — averages range from $25,161 (Cancer) to $25,805 (Obesity), a spread of under $650. Insurance provider also shows minimal billing variation.
August records peak admissions (4,832), with summer months consistently elevated. February is the lowest (4,255) — partly a shortest-month effect.
High billing segment (>$30K) is the largest across every condition. Obesity leads in the High segment (3,876 patients). Using SQL PERCENT_RANK(), patients were assigned billing percentiles within their condition group — enabling outlier flagging for insurance review.
Data quality issues detected: duplicate patient entries with identical billing amounts, and negative billing values flagged as anomalies — both documented and handled in the analysis.



👤 Author

Naitik Bisht — Self-Taught Data Analyst
B.Sc. Mathematics | Zakir Husain Delhi College, University of Delhi
