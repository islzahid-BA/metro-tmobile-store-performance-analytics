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

![Project Workflow](docs/project_workflow_diagram.png)

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

## Tools Used

The following tools were used in this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Prophet
- Statsmodels
- Power BI
- Excel
- GitHub
- Notion for project planning

---

## How to Run This Project

1. Clone the repository
2. Open the project folder
   cd metro-tmobile-store-performance-analytics
3. Install the required Python libraries
   pip install -r requirements.txt
4. Run the notebooks in order
   01_data_cleaning_and_eda.ipynb
   02_kpi_framework_and_store_performance.ipynb
   03_upselling_efficiency_and_segmentation.ipynb
   04_forecasting_models.ipynb
   05_dashboard_data_preparation.ipynb

   The notebooks are located in the notebooks/ folder.
5. Open the Power BI dashboard
   dashboard/Metro_TMobile_Dashboard_Demo_Public.pbix

Some file paths may need to be adjusted depending on whether the project is run locally, in Google Colab, or on another machine.

---

## Limitations
This project has several important limitations:
- The public dataset is synthetic and does not show real company performance.
- The original company data is confidential and is not included in this repository.
- Store names, values, and some fields were created for demonstration purposes.
- The analysis uses store-level aggregated data, not customer-level data.
- KPI relationships should be interpreted as associations, not causal relationships.
- Forecasting outputs are planning estimates and should not be treated as exact predictions.
- The Power BI dashboard may require path updates after downloading the repository.

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
