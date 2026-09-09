BlinkIT Grocery Sales Analytics

Interactive Power BI dashboard for analyzing grocery sales performance across products, outlets, outlet formats, location tiers, outlet sizes, and establishment years.

📊 Project Overview

This project transforms the BlinkIT grocery dataset into an interactive Power BI dashboard designed for business-oriented sales analysis.

Dataset: 8,523 records × 12 fields
Unique outlets: 10
Item categories: 16
Primary KPI: Total Sales

Dashboard Preview

Place an exported dashboard screenshot at:

screenshots/dashboard.png

🎯 Business Questions

What is the overall sales performance?

Which outlet types contribute the most sales?

Which location tier performs best?

How does outlet size relate to sales?

Which item categories generate the most sales?

How do Low Fat and Regular products compare?

How does performance vary by establishment year?

🔑 Key KPIs

KPI

Value

Total Sales

1,201,681.49

Total Outlets

10

Average Sales

140.99

Average Rating

3.97

🛠️ Tools

Microsoft Power BI

DAX

Power Query

Microsoft Excel

Git / GitHub

Markdown

🧩 Dashboard Features

KPI cards

Outlet location filtering

Outlet size filtering

Metric selector

Outlet location analysis

Outlet size analysis

Establishment-year analysis

Fat-content analysis

Item-type analysis

Detailed analytical matrix

📁 Repository Structure

blinkit-grocery-sales-analytics/
├── README.md
├── docs/
│   ├── PROJECT_DESIGN_DOCUMENT.md
│   └── SOLUTION_DESIGN_DOCUMENT.md
├── powerbi/
│   └── Blinkit.pbix
├── data/
│   └── README.md
├── screenshots/
│   └── dashboard.png
├── LICENSE
└── .gitignore

📚 Documentation

Project Design Document

Solution Design Document

⚠️ Data Quality Note

The source dataset contains inconsistent item fat-content labels, including Low Fat, LF, low fat, Regular, and reg. A production-grade implementation should normalize these categories before reporting.

The dataset also contains 1,463 missing Item Weight values.

🚀 Future Enhancements

Star-schema semantic model

Profit and margin analysis

Outlet drill-through pages

Top-N outlet/category analysis

Forecasting

Inventory analytics

Automated data-quality checks

Power BI Service deployment

PBIP-based source control

📌 Portfolio Note

This project demonstrates practical skills in:

Data Preparation → Data Modeling → DAX → Visualization → Business Analysis → Documentation
