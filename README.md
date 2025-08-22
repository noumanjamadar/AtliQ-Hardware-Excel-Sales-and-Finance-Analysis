#  📊 AtliQ-Hardware-Excel-Sales-and-Finance-Analysis
  
## 📌 Table of Contents  
- [Project Overview](#-project-overview)  
- [Steps & Tasks Performed](#-steps--tasks-performed)  
- [Key Insights from Reports](#-key-insights-from-reports)  
- [Project Deliverables](#-project-deliverables)  
- [Reports Preview](#-reports-preview)  
- [Tools & Technologies Used](#-tools--technologies-used)  
- [Skills Demonstrated](#-skills-demonstrated)  
- [Conclusion](#-conclusion)  

---

## 📌 Project Overview  
This project is a **data analysis case study** on **AtliQ Hardware**, a fictional company that sells hardware products such as **computers, PCs, and accessories (mouse, keyboards, etc.)**.  
AtliQ Hardware distributes products through major retailers (e.g., **Croma, Amazon, Flipkart, Costco**) and also via its **exclusive stores and e-store**.  

The dataset contains **1M+ records** across multiple tables, including:  
- `dim_customer`  
- `dim_product`  
- `dim_market`  
- `fact_sales_monthly` (with freight cost, manufacturing cost, sales)  
- `dim_date` (with fiscal year logic for reporting)  
- `target_sales`  

The fiscal year for AtliQ Hardware runs from **September to August**.  
All reporting (quarters, fiscal years) is based on this business calendar rather than the standard Jan–Dec calendar.  

---

## 🛠️ Steps & Tasks Performed  

### 🔹 Data Cleaning & Preparation  
- Used **Excel formulas** and **Power Query** to:  
  - Remove duplicates  
  - Handle missing values  
  - Transform raw data into structured tables  
- Created a **date dimension table** with **fiscal year mapping (Sep–Aug cycle)** and assigned quarters accordingly for accurate P&L and trend analysis.  

### 🔹 Data Modeling  
- Built relationships in **Power Pivot Data Model** between dimension and fact tables.  
- Performed **data modeling** for accurate reporting.  

### 🔹 Measures & KPIs (DAX)  
Created custom measures using **DAX** in Power Pivot, including:  
- **Net Sales by Fiscal Year** (e.g., Net Sales 2019, 2020, 2021 using `CALCULATE` with FY filter)  
- **Total Net Sales**  
- **Gross Margin (GM)** and **GM%**  
- **Target Sales vs Actual Sales** variance (%)  

### 🔹 Reporting & Analysis  
Developed multiple **Excel Pivot Reports** with filters for:  
- **Customer-wise Net Sales** (2019–2021) and YoY growth %  
- **Country-wise Sales Performance vs Targets**  
- **P&L Statement by Fiscal Year** (Net Sales, COGS, GM, GM%)  
- **Quarterly & Monthly Trends** (2019–2021, based on Sep–Aug fiscal year)  
- **Market-level Performance Analysis**  

### 🔹 Visualization & Formatting  
- Applied **conditional formatting** (3-color scale, data bars) to highlight high/low performers.  
- Added slicers & filters for interactive analysis (region, market, division, customer).  
- Highlighted growth trends and sales variances.  

---

## 📈 Key Insights from Reports  
- **Strong YoY growth:** Net sales grew from **$87.5M (2019) → $196.7M (2020) → $598.9M (2021)** (~304% growth vs 2020).  
- **India & USA** emerged as the top-performing markets in 2021.  
- Some regions (e.g., **Canada, USA, South Korea**) missed their 2021 targets by ~8–12%.  
- **Gross Margin %** declined slightly from ~41% (2019) to ~36% (2021), highlighting rising COGS.  
- Retailers like **Amazon, Flipkart, AtliQ e-Store, and Reliance Digital** drove major sales growth.  

---

## 📂 Project Deliverables  
- ✅ Cleaned and transformed **Excel data model**  
- ✅ Pivot table reports with **DAX-based KPIs**  
- ✅ Conditional formatting and slicers for interactivity  
- ✅ Multiple **PDF reports** (customer, country, P&L, market performance)  

---

## 📑 Reports Preview  
All reports are included as individual PDF files in this repository.  
They cover:  
- Customer sales growth (2019–2021)  
- Country-wise performance vs target  
- P&L reports by year and quarter  
- Market profitability breakdown  
📂 You can also explore the **interactive Excel file** with Power Query, Power Pivot, and DAX measures here:  
[Download Excel Workbook](https://docs.google.com/spreadsheets/d/1diw82OG7qvXQ1bwAK9a0bagbEHEUd8aA/edit?usp=drive_link&ouid=108637359398456633790&rtpof=true&sd=true)
---

## 🚀 Tools & Technologies Used  
- **Microsoft Excel** (Power Query, Power Pivot, Pivot Tables, Conditional Formatting, DAX)  
- **Data Modeling & Cleaning**  
- **Interactive Reports & Dashboards**  

---

## 🧑‍💻 Skills Demonstrated  
- Data Cleaning & Transformation (Power Query, Excel Formulas)  
- Data Modeling (Power Pivot, Star Schema Design)  
- DAX Calculations & KPIs (Net Sales, Gross Margin, Variance %)  
- Business Reporting (P&L, Customer/Country Sales, Target vs Actual)  
- Visualization (Conditional Formatting, Interactive Slicers & Filters)  
- Storytelling with Data (Business insights for decision-making)  
- Advanced Date Handling (**Custom Fiscal Year: Sep–Aug, Quarter Calculations**)  

---

## 📌 Conclusion  
This project demonstrates how **Excel can be used as a powerful BI tool** for analyzing large datasets (>1M records), performing **data modeling with Power Pivot**, and building **interactive business reports** without external BI tools.  

