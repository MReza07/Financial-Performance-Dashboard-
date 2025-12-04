## 📊 Financial Performance Dashboard

Power BI | Sales & Profitability | Forecasting | KPI Tracking

A comprehensive Financial Analysis Dashboard built in Power BI to evaluate company performance across products, segments, and countries. This dashboard provides actionable insights into sales trends, profit margins, product quality, YoY/MoM growth, and cost efficiency—empowering organizations to make data-driven business decisions.


📷 Dashboard Preview https://github.com/MReza07/Financial-Performance-Dashboard-/tree/main/Schreenshots


## 📁 Project Overview

This dashboard consolidates key financial metrics to help stakeholders monitor business health, compare current performance vs last year, and understand profitability at multiple levels.
It supports strategic planning, budgeting, and operational improvements.

## ⭐ Key Performance Indicators (KPIs)

Sales – Current VS Last Year

Profit – Current VS Last Year

Profit % – Current VS Last Year

Product Sales Count – Current VS Last Year

Product Quality Score

COGS – Current VS Last Year
Each KPI includes:

✔ Trend comparison
✔ Percentage change
✔ Visual indicators for improvement or decline

## 📊 Dashboard Highlights

1️⃣ Product-Level Analysis

Total Sales & Total Profit by Product

Quality Score vs Profit Performance

MoM Sales & Profit Growth

Yearly Sales Trend (YOY Growth)

2️⃣ Segment-Level Analysis

Total Profit by Segment

Profit Margin Comparison

Performance of Government, Small Business, Channel Partners, Midmarket & Enterprise

3️⃣ Country-Level Analysis

Total Profit by Country

Profit Margin by Country (Germany, France, Canada, US, Mexico)

4️⃣ Interactive Filters

Product Filter

Year Filter

Month Selector

These allow users to explore the data dynamically and identify specific trends.


## 📂 Project Structure

Financial-Dashboard
│
├── 📄 Dataset/

│   └── Financial Dataset.xlsx
│
├── 📄 PBIX/

│   └── Financial Dashboard.pbix
│
├── 📄 Screenshots/

│   └── Financial Dashboard.PNG

    └──   MOM Profit Growth.PNG

    └── Profit Margin by Country.PNG

    └── Total Profit & Total Sales by product.PNG

    └── Total profit by segment.PNG
│
└── 📄 README.md


## 📐 Sample DAX Measures

DAX

Total Sales = SUM(Financial_Data[Sales])

Total Profit = SUM(Financial_Data[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

YoY Sales Growth % =

VAR CurrentYear = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))

RETURN DIVIDE([Total Sales] - CurrentYear, CurrentYear)

MoM Profit Growth =

VAR PrevMonth = CALCULATE([Total Profit], PREVIOUSMONTH(Date[Date]))

RETURN [Total Profit] - PrevMonth


## 🎯 Business Outcomes

Identifies high-profit products and low-performing segments

Reveals market opportunities by region

Tracks year-over-year and month-over-month financial growth

Helps optimize product quality, pricing, and COGS

Enables data-driven budgeting and forecasting


## 🚀 How to Open the Dashboard

Navigate to the PBIX folder

Click Download → Raw to download the .pbix file

Open the file in Power BI Desktop

Use the slicers (Product, Year, Month) to interact with the dashboard


## 🛠️ Tools & Technologies

Power BI Desktop

Power Query (ETL)

DAX (Data Modeling & Measures)

Excel Dataset

Interactive Visualizations

## 📜 License

This project is distributed under the MIT License.

## 📬 Contact

Md. Rezaul Repon

Data Analyst – Power BI | SQL | Python

📧 Email: reazulrepon@gmail.com

🔗 GitHub: https://github.com/MReza07





