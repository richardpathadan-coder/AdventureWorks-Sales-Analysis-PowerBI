# 📊 AdventureWorks Sales & Budget Analysis – Power BI

## 🔍 Project Overview
This project demonstrates an end-to-end **Power BI Business Intelligence workflow** using **Excel-based data** as the source.

The data was **loaded from Excel files**, **cleaned and transformed using Power Query**, and then **manually modeled by creating relationships between tables** to ensure accurate analysis.

The final Power BI dashboard analyzes **sales performance versus budget** for AdventureWorks, enabling stakeholders to:
- Track overall sales and budget performance
- Identify category-level and monthly variances
- Analyze trends over time
- Support data-driven business decisions using interactive visuals and KPIs


---
## 🗂 Dataset Description
This project uses **two Excel files** as the data source:

- **Excel sheet named [Budget](Budget.xlsx)**
- Contains budget allocation data by product category and month (as shown in the uploaded dataset screenshot).

- **Excel sheet named [AdventureWorks_Database](AdventureWorks_Database.xlsx)**
- Contains detailed sales transaction data. All sales-related metrics and insights in the dashboard are derived from this file.

### Dataset Details
- **Source:** Excel files (Sales & Budget)
- **Time Period:** January 2023 – December 2023
- **Granularity:** Monthly sales and budget data
- **Categories:** Bikes, Accessories, Clothing
- **Metrics:** Sales Amount, Budget Amount

The data from both Excel files was loaded into Power BI, cleaned and transformed using **Power Query**, and then combined through **manually created relationships** to support accurate sales vs budget analysis.

- **Screenshots of the Excel sheets which the data was taken**
  ![Excel](Exceldatascreenshot.png)

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- Power Query (data transformation and cleaning)  
- DAX (calculated measures and KPIs)  
- Microsoft Excel  
- GitHub  

---

## 📐 Data Modeling & Transformations
- Cleaned and standardized category and product fields
- Transformed wide-format monthly data into an analytical model
- Created relationships between fact and dimension tables
- Ensured data accuracy for time-based and category analysis

---

## 📈 Key KPIs & DAX Measures
- Total Sales  
- Total Budget  
- Variance (Sales – Budget)  
- Variance %  
- Sales by Category  
- Monthly Sales Trend  

These KPIs provide both high-level summaries and detailed insights.

---

## 🧠 Business Insights
- Bikes generate the highest revenue but show the largest negative budget variance
- Accessories consistently perform close to or above budget
- Clothing has steady but lower revenue contribution
- Strong sales growth observed in Q4 (October–December)
- August records the highest negative monthly variance, indicating a need for reforecasting

---

## 🖥 Dashboard Preview

### Executive Summary & KPIs
![Dashboard Overview](PowerBireprtshot.png)

---

