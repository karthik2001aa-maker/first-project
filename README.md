# Sales Dashboard Analysis | Power bi 
An end-to-end Data sales Analytics Dashboard Project to analyze sales, profit, customers, products, regions, returns, and overall retail performance. 
# 📊 Sales Performance Dashboard 
<img width="509" height="284" alt="Screenshot 2026-09-21 002756" src="https://github.com/user-attachments/assets/3c8063eb-f8cd-43de-99bc-4c822597345a" /> <img width="505" height="285" alt="Screenshot 2026-09-21 115443" src="https://github.com/user-attachments/assets/47056290-c7fa-4fc0-849f-21a1f764cb93" />
# 📌 Project Overview 

The Sales Dashboard is a Business Intelligence project developed using Power BI and the sales Dataset. 

The project transforms raw retail data into an interactive dashboard that helps analyzes

 • Years, Months, Regions, Subcategory, Gender, Category (Slicers) 
 
 • Total Gross sales, Total Net Sales, Total Profit 
 
 • Profit by Segment 
 
 • Cost And Profit by category
 
 • Sale by products
 
 • Gross Sale and Net Sale by City 
 
 • Sale by Category
 
 • Sale by Pamentmode 
 
 • Total customer, Average Sales, Average profit
 
 • Sale by Months
 # 🗂️ Dataset 

The project uses the sales Dataset in Excel format. 

The dataset contains four tables:

 • Sales Table     - (Fact Table) 

 • Product Table   - (Dimension Table) 

 • Customers Table - (Dimension Table) 

 • Calendar Table   - (Dimension Table) 

# 📊 Dataset Summary     

Total Sales               =                                228.18M 

Total Net sale            =                                212.99M 

Total Profit              =                                68.73M 

Total unit price          =                                1.25M 

Total Customer            =                                200 

Average Sale               =                               228.18M 

Average profit             =                               68.78k 

Total Quantity             =                               5436 

# 🛠️ Tools & Technologies 
## 1️⃣ Data Import 
The sales Excel dataset was imported into Power BI. The following tables were used

  • Sales 

  • Products 

  • Customers 

  • Calendar 

## 2️⃣ Data Cleaning & Transformation 

Power Query was used to prepare data for analysis. 

The data preparation process included: 

  • Checking data types 

  • Formatting date fields 

  • Remove duplicate values 

  • Handling missing values 

  • Cleaning data 

  • Preparing tables for analysis 

## 3️⃣ Data Modeling 

If you want a Power BI star-schema data model, use these 4 tables: 

   • Sales Table → Fact Table 

   • Product Table → Dimension Table 

   • Customers Table → Dimension Table 

   • Calendar Table → Dimension Table 

### Relationship 

  Product Table ─────┐   

Customers Table ──   ┼ Sales Table  

Calendar Table   ────┘ 

## 4️⃣ DAX Measures 

Created DAX measures for important business KPIs such as: 

   • Total Sales     

   • Average Sales 

   • Average profit 

   • Total Quantity     

   • Total Customer      

## 5️⃣ Dashboard Development 

Created an interactive dashboard using: 

   • KPI Cards 

   • Bar Charts 

   • Stacked Area Chart 

   • Donut Chart 

   • Column Charts 

   • Pic Chart 

   • Treemap Chart 

   • Line Charts 

   • Tables 

   • Slicers 

   • Conditional Formation 
