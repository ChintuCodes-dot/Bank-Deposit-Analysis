📊 Account & Deposit Analysis Dashboard

📌 Project Overview

The Account & Deposit Analysis Dashboard is an interactive Power BI project developed to analyze account and deposit performance on a weekly basis.

The dashboard allows users to select a reporting period and analyze deposit balances and account volumes across different business dimensions such as Region, Product, Group, and Line of Business.



🎯 Project Objectives

- Analyze weekly deposit balance performance.
- Analyze weekly account performance.
- Provide interactive Period From and Period To selection.
- Display weekly performance dynamically using WK1, WK2, WK3....
- Analyze performance across different business segments.
- Provide an easy-to-use interactive reporting solution.
- Help identify weekly trends and performance differences across regions and products.


🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Excel / Source Dataset


📂 Dataset

The primary dataset used in this project is AccountDepositsData.

The dataset contains account and deposit information along with business and time-related attributes used for analysis.

Key Data Fields

- Date
- Accounts
- Balance
- Year
- Month
- Year-Month
- Week Number
- Week Label
- Region
- Product
- Group
- Line of Business


📅 Date & Period Analysis

A dedicated date structure was created to support time-based analysis.

The dashboard uses separate Period From and Period To selections to provide flexible period-based analysis.

The Period To selection dynamically responds to the selected Period From value.

For example:

Period From: 2022-Jan

Period To options begin from:

2022-Feb → 2022-Mar → 2022-Apr → ...

This allows users to analyze only valid reporting ranges.


📈 Weekly Analysis

A major feature of the dashboard is its dynamic weekly analysis.

The dashboard displays weekly performance using sequential labels such as:

WK1 → WK2 → WK3 → WK4 → ...

The weekly analysis is designed to display all applicable weeks between the selected Period From and Period To.

For example:

2022-Jan → 2022-Feb

WK1 → WK2 → ... → WK10

2022-Jan → 2022-Mar

WK1 → WK2 → ... → WK14

The weekly sequence is designed to restart from WK1 when a new reporting period is selected.


💰 Deposit Analysis

The Deposit Analysis page focuses on monitoring deposit balance performance over time.

Key Features

- Weekly deposit trend analysis
- Total deposit balance monitoring
- Period From and Period To selection
- Region-level analysis
- Product-level analysis
- Group-level analysis
- Line-of-Business analysis
- Interactive filtering

Key Metric

Total Deposits / Balance

This page helps users understand how deposit balances change across the selected reporting period.


👥 Account Analysis

The Account Analysis page focuses on monitoring account performance on a weekly basis.

Key Features

- Weekly account trend analysis
- Total account monitoring
- Dynamic period selection
- Region-level analysis
- Product-level analysis
- Group-level analysis
- Line-of-Business analysis
- Interactive filtering

Key Metric

Total Accounts

This page helps users identify account trends and compare performance across different business segments.


🔄 Dynamic Filtering

The dashboard provides multiple interactive filters:

Filter| Purpose
Period From| Select the starting reporting period
Period To| Select the ending reporting period
Region| Analyze regional performance
Product| Analyze product performance
Group| Analyze group-level performance
Line of Business| Analyze business-line performance

All relevant visuals update according to the selected filters.


📊 Dashboard Pages

1. Landing Page

Provides navigation and an overview of the dashboard.

2. Deposit Analysis

Provides weekly analysis of deposit balances across different business dimensions.

3. Account Analysis

Provides weekly analysis of account volumes across different business dimensions.
Example:

![Landing Page](https://github.com/ChintuCodes-dot/Bank-Deposit-Analysis/blob/main/Landing%20Page.png)

![Deposits Trends Analysis]()

![Accounts Trends Analysis]()




⚙️ Key Features

- Interactive Power BI dashboard
- Dynamic period selection
- Weekly trend analysis
- Sequential weekly visualization
- Deposit performance analysis
- Account performance analysis
- Region-wise analysis
- Product-wise analysis
- Group-wise analysis
- Line-of-Business analysis
- Interactive slicers and filters
- Dedicated date structure
- Business-focused data visualization


🚧 Project Status

Status: In Progress

Completed

- Prepared the Account & Deposit dataset.
- Created the date structure for time-based analysis.
- Created Period From and Period To selections.
- Implemented dynamic period filtering.
- Created account and deposit KPIs.
- Developed weekly analysis logic.
- Developed the Deposit Analysis page.
- Developed the Account Analysis page.
- Added Region, Product, Group, and Line-of-Business filters.
- Created interactive dashboard visualizations.

Currently Working On

- Finalizing the dynamic weekly axis.
- Validating weekly values against the source data.
- Completing final dashboard testing and validation.


💡 Business Value

This dashboard converts raw account and deposit data into an interactive reporting solution that helps users:

- Monitor deposit performance.
- Track account volumes.
- Identify weekly trends.
- Compare regions and products.
- Analyze different business segments.
- Explore performance for customized reporting periods.
- Reduce dependency on manual analysis and reporting.


📌 Project Summary

The Account & Deposit Analysis Dashboard demonstrates practical experience in Power BI, data modeling, data visualization, interactive filtering, and business analysis.

The project focuses on transforming account and deposit data into an interactive weekly reporting solution that enables users to quickly analyze performance across different periods and business dimensions.
