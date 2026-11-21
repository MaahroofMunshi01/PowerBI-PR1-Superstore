# Power BI PR1 — Superstore Sales & Performance Dashboard

## Project Overview

This project demonstrates the use of Microsoft Power BI for analyzing retail sales data and presenting important business metrics through an interactive dashboard.

Using the Sample Superstore dataset, the project explores sales trends, profit distribution, product category performance, and regional business activities.

The dashboard is designed to make business data easier to understand through KPI indicators, charts, slicers, and interactive filtering.

## Dataset Information

- **Dataset:** Sample Superstore Sales Dataset
- **Data Source:** Kaggle
- **Format:** CSV
- **Total Records:** Approximately 9,994
- **Domain:** Retail and Business Sales Analytics

## Technologies & Tools

- Power BI Desktop — Dashboard development and visualization
- Power Query Editor — Data cleaning and transformation
- DAX — Calculated measures and business metrics
- CSV — Source data format

## Repository Structure

```text
PowerBI-PR1-Superstore/
│
├── SampleSuperstore.csv
├── PR1_Mahroof.pbix
├── README.md
├── LICENSE
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── documentation/
│
├── documentation/
│   ├── project_overview.md
│   ├── business_requirements.md
│   ├── data_cleaning.md
│   ├── dax_measures.md
│   ├── dashboard_design.md
│   └── insights_and_findings.md
│
├── reports/
│   ├── report_summary.md
│   ├── page1_dashboard.md
│   └── page2_datatable.md
│
├── theme/
├── screenshots/
├── assets/
├── dax/
├── queries/
└── resources/
```

## Development Workflow

### 1. Dataset Import
- Imported the Sample Superstore CSV file into Power BI Desktop.
- Connected the dataset to the Power BI reporting environment.

### 2. Data Cleaning & Preparation
- Performed data cleaning using Power Query Editor.
- Applied 8+ transformation steps to prepare the dataset.
- Reviewed column formats and data types.
- Prepared the required fields for visualization and analysis.

### 3. Key Performance Indicators (KPIs)

Created four KPI cards to monitor important business metrics:

| KPI | Purpose |
|---|---|
| Total Sales | Measures overall sales revenue |
| Total Profit | Shows the profit generated |
| Total Quantity | Displays the total quantity sold |
| Average Discount | Represents the average discount offered |

### 4. Charts & Visualizations

Developed the following charts:

- **Sales by Category:** Compares sales performance across product categories.
- **Profit by Region:** Highlights profit contribution from different regions.

### 5. Interactive Slicers

Implemented two slicers for dynamic report exploration:

- Region Slicer
- Category Slicer

### 6. Filter Management
- Applied page-level filtering.
- Configured visual-level filtering.
- Tested filter behavior across dashboard elements.

### 7. Dashboard Theme & Formatting
- Integrated a custom Power BI theme.
- Formatted charts, KPI cards, and report elements.
- Maintained a clean and consistent visual layout.

### 8. Visual Interactions
- Configured interactions between dashboard visuals.
- Tested at least three visual interaction pairs.
- Verified that selections update related visualizations correctly.

## Dashboard Preview

### Dashboard — Page 1

![Sales Dashboard](screenshots/page1_dashboard.png)

### Data View — Page 2

![Data Table](screenshots/page2_datatable.png)

## Analysis & Insights

The report provides an opportunity to examine:

- Total business sales and profit.
- Performance differences between product categories.
- Regional contribution to overall profitability.
- Product quantity and discount trends.
- Sales performance under different filter selections.

## Running the Project

To explore the dashboard:

1. Download or clone the repository.
2. Open the `PR1_Mahroof.pbix` file.
3. Launch it using Microsoft Power BI Desktop.
4. Navigate between the available report pages.
5. Apply Region and Category slicers.
6. Explore charts, KPIs, and interactive visual elements.

## Deliverables

| Component | Repository Location |
|---|---|
| Power BI Report | `PR1_Mahroof.pbix` |
| Dataset | `SampleSuperstore.csv` |
| Documentation | `documentation/` |
| DAX Calculations | `dax/` |
| Power Query Resources | `queries/` |
| Dashboard Screenshots | `screenshots/` |
| Theme Configuration | `theme/` |
| Additional Resources | `resources/` |

## Author

**Mahroof**

Power BI | Data Analytics | Business Intelligence

## Acknowledgement

Thanks to Kaggle for providing the Sample Superstore dataset used in this project. This work is intended for educational purposes and practical experience in business intelligence and data visualization.
