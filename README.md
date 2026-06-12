End-to-end data analysis of a real-world healthcare dataset — from raw data to actionable business insights using Python, SQL, and Power BI.


📊 Dashboard Preview


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


Patients aged 40–70 account for the majority of admissions and the highest average billing
Certain conditions (e.g. diabetes, hypertension) show strong correlation with longer stays and higher costs
Seasonal admission peaks observed in winter months — relevant for hospital resource planning
Risk segmentation reveals a small high-cost patient group that accounts for a disproportionate share of billing



👤 Author

Naitik Bisht — Self-Taught Data Analyst
B.Sc. Mathematics | Zakir Husain Delhi College, University of Delhi
