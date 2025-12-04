📊 Financial Performance Dashboard

Power BI | Sales & Profitability | Forecasting | KPI Tracking

A comprehensive Financial Analysis Dashboard built in Power BI to evaluate company performance across products, segments, and countries. This dashboard delivers meaningful insights into sales trends, profit margins, product quality, YoY/MoM growth, and cost efficiency, helping organizations make smarter, data-driven decisions.

📷 Dashboard Preview

🔗 View Screenshots:
https://github.com/MReza07/Financial-Performance-Dashboard-/tree/main/Schreenshots

📁 Project Overview

This dashboard brings together key financial metrics to help stakeholders:

Monitor overall business performance

Compare current vs last year results

Understand profit and sales distribution across multiple dimensions

Improve planning, budgeting, and forecasting

It provides a clear and interactive view of critical performance indicators to support strategic decision-making.

⭐ Key Performance Indicators (KPIs)

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

📊 Dashboard Highlights

1️⃣ Product-Level Analysis

Total Sales & Total Profit by Product

Quality Score vs Profit Performance

Month-over-Month (MoM) Sales & Profit Growth

Year-over-Year (YoY) Sales Trend

2️⃣ Segment-Level Analysis

Total Profit by Segment

Segment-wise Profit Margin

Performance comparison:
Government | Small Business | Channel Partners | Midmarket | Enterprise

3️⃣ Country-Level Analysis

Total Profit by Country

Country-wise Profit Margins (Germany, France, Canada, US, Mexico)

4️⃣ Interactive Filters

Product Filter

Year Filter

Month Selector

These filters help users explore the data dynamically and uncover deeper insights.

📂 Project Structure
Financial-Dashboard
│
├── 📄 Dataset/
│   └── Financial Dataset.xlsx
│
├── 📄 PBIX/
│   └── Financial Dashboard.pbix
│
├── 📄 Screenshots/
│   ├── Financial Dashboard.PNG
│   ├── MOM Profit Growth.PNG
│   ├── Profit Margin by Country.PNG
│   ├── Total Profit & Total Sales by Product.PNG
│   └── Total Profit by Segment.PNG
│
└── 📄 README.md

📐 Sample DAX Measures
Total Sales =
SUM(Financial_Data[Sales])

Total Profit =
SUM(Financial_Data[Profit])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

YoY Sales Growth % =
VAR CurrentYear =
    CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))
RETURN
    DIVIDE([Total Sales] - CurrentYear, CurrentYear)

MoM Profit Growth =
VAR PrevMonth =
    CALCULATE([Total Profit], PREVIOUSMONTH(Date[Date]))
RETURN
    [Total Profit] - PrevMonth

🎯 Business Outcomes

Identifies high-profit products and underperforming segments

Reveals regional growth opportunities

Tracks year-over-year and month-over-month financial performance

Helps optimize pricing, product quality, and COGS

Supports accurate budgeting and forecasting

🚀 How to Open the Dashboard

Navigate to the PBIX folder

Click Download → Raw to download the .pbix file

Open it using Power BI Desktop

Use filters (Product, Year, Month) to explore insights interactively

🛠️ Tools & Technologies

Power BI Desktop

Power Query (ETL & Data Cleaning)

DAX (Measures & Modeling)

Excel Dataset

Interactive Visual Analytics

📜 License

This project is distributed under the MIT License.

📬 Contact

Md. Rezaul Repon
Data Analyst – Power BI | SQL | Python
📧 Email: reazulrepon@gmail.com

🔗 GitHub: https://github.com/MReza07
