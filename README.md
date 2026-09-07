# Metro by T-Mobile Store Performance Analytics

This repository contains a public demo version of my practicum project for a retail store performance analytics case focused on Metro by T-Mobile stores in the Tulsa market.

The original practicum project used company-provided store performance data. Because the original data is confidential, this public GitHub version uses synthetic demo data that follows a similar structure. The goal of this version is to show the full analytics workflow: data cleaning, KPI analysis, store comparison, forecasting, early warning logic, and Power BI dashboarding.

---

## Project Purpose

The main goal of this project was to turn store-level performance reports into a cleaner analytics process that can help answer questions such as:

- Which stores are performing strongly?
- Which stores have high volume but lower efficiency?
- How do activation, account gross, accessory profit, and productivity metrics vary by store?
- What KPIs are associated with stronger performance?
- Can we create a simple forecasting and early-warning process for store monitoring?
- How can the results be shown in a dashboard for business users?


---

## Important Note About Data

The data in this repository is synthetic and was created for public demonstration only.

The original company data is not included in this repository. Store names, values, and additional fields in the public dataset are for demonstration purposes and should not be interpreted as real company performance.

The early-warning examples are also demonstration outputs created to show how warning flags can appear in a dashboard.

---

## Project Workflow

The project followed a step-by-step analytics workflow.

![Project Workflow](docs/project_workflow_infographic.png)

Main workflow:

1. Project Planning & Scope  
2. Data Quality Review  
3. Exploratory Data Analysis  
4. Store Performance Analysis  
5. KPI Relationship Analysis  
6. Forecasting Model  
7. Early Warning Analysis  
8. Visualization & Dashboard  
9. Final Report & Recommendations  

---

## Repository Structure

```text
metro-tmobile-store-performance-analytics/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_data_cleaning_and_eda.ipynb
│   ├── 02_kpi_framework_and_store_performance.ipynb
│   ├── 03_upselling_efficiency_and_segmentation.ipynb
│   ├── 04_forecasting_models.ipynb
│   └── 05_dashboard_data_preparation.ipynb
│
├── data/
│   └── raw/
│       ├── demo_daily_sales_messy.csv
│       ├── demo_monthly_kpi_messy.csv
│       └── kpi_dictionary.csv
│
├── dashboard/
│   ├── Metro_TMobile_Dashboard_Demo_Public.pbix
│   ├── dashboard_metro_by_tmobile.gif
│   └── screenshots/
│       ├── 01_overview.png
│       ├── 02_store_comparison.png
│       ├── 03_upselling_efficiency.png
│       └── 04_forecast_early_warning.png
│
└── docs/
    ├── kpi_dictionary.md
    ├── project_workflow.md
    └── project_workflow_infographic.png
