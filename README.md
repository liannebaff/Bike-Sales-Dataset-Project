# 🚲 Bike Sales Dataset Project
 
### 📝 Project Summary
This repository contains an Excel-based analysis of a synthetic bike sales dataset. The project demonstrates the use of pivot tables and pivot charts for data analysis to identify how customer demographics (age, location) affect revenue, and to assess how revenue and profit have changed over time.

### 🎯 Key skills Demonstrated:
`Data exploration` `PivotTables and PivotCharts`  

### 🗂️ Dataset Overview
The dataset contains synthetic bike sales transactions. Each row represents a single order, including **customer demographics** (age, age group, gender, country and state), **product information** (product, product category and subcategory, unit cost) and **sales metrics** (unit price, order quantity, revenue, profit and cost) and date of the order.
Customers have been classified into age groups based on their age, these are below:

| Age (years)        | Age Group             |
|--------------------|-----------------------|
| < 25               |Youth                  |
| 25 - 34            | Young Adults          |
| 35 - 64            | Adults                |
| > 64               | Seniors               |

---
### 🛠️ Excel Skills Demonstrated
#### ☑️ PivotTables & PivotCharts
- Built pivot tables to analyse revenue and profit by year, and revenue by customer age and country.
- Created Pivot charts (stacked column and clustered column charts) to visualise data.

---
### 🧩Process
 The goal of this project was to explore and visualise the dataset in order to uncover trends in revenue and profit over the years and understand how customer demographics influence sales. Here's how I worked through the Excel project, step by step.

 #### ⤵️ Data Loading and Preparation
 - Imported the dataset into Excel and reviewed structure and key variables.
 - Checked that dates, numbers and text were in an appropriate format and that there were no missing values
 - Checked the formulas within the calculated fields (Revenue, Cost and Profit) were correct.

#### 🔀 PivotTables & PivotCharts
- Built pivot tables and charts for easy grouping, comparison, analysis and visualisation of the dataset.
- Screenshots of pivot tables and charts are included in the **Analysis & Findings** section below along with key insights
- Pivot table summary below:
  
| Name                        | Rows     | Columns          | Values                        |
|-----------------------------|----------|------------------|-------------------------------|
| Revenue and Profit by Year  | Year     | N/A              | Annual Profit, Annual Revenue |
| Revenue by Country          | Country  | Product Category | Sum of Revenue                |
| Revenue by Age Group        | Age Group| N/A              | Sum of Revenue                |

---

### 📈 Analysis & Key Insights

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **a) Revenue and Profit by Year**

<img width="729" height="584" alt="image" src="https://github.com/user-attachments/assets/4508c553-6e03-4146-aacd-f7dcf4f041f4" />


🧠 **Key Insights**
- Both annual revenue and profit show a steady increase from 2017 to 2021.
- The highest revenue was in 2021 with a revenue $29,747,226 and a profit of $12,986,202. <br> <br>


&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **b) Revenue by Country**

<img width="654" height="642" alt="image" src="https://github.com/user-attachments/assets/9597a0fc-6771-425a-a71f-00d5a8c74c4d" />


🧠 **Key Insights**
- The United States is the top revenue-generating country overall, followed by Australia and the United Kingdom.
- Bikes dominate revenue across all countries, particularly in the United States ($21,551,497) and Australia ($20,231,586). <br> <br>


&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **c) Revenue by Age Group**

<img width="814" height="589" alt="image" src="https://github.com/user-attachments/assets/a4473028-29c6-4dbb-b981-f26090d6f69b" />


🧠 **Key Insights**
- Adults generate the highest revenue ($47,323,876) making them the most valuable customer base. Young adults are the second largest purchasing group ($34,310,905).
- Youth ($13,201,837) and Seniors ($339,700) account for a small proportion of total revenue.

---
### 🪞Reflections 
- Revenue and profit grew consistently between 2017 and 2021, indicating strong overall business performance.
- The United States and Australia are the largest revenue-generating markets, suggesting geographic priorities for marketing.
- Bikes are the dominant product category across all countries, highlighting the importance of inventory planning to maintain bike supply.
- Adults and Young Adults are the largest purchasing groups, indicating marketing efforts could focus on these groups.
- Product, demographic and regional trends can inform inventory planning, marketing strategy and marketing campaigns.

---
### 📁 Files in This Repository
- **[Bike_Sales_Dataset_Analysis.xlsx](files/bike_sales_dataset_analysis.xlsx)**
&nbsp;  
  **Worksheets:**
  - <small><strong>Sales Data:</strong> bike sales dataset.</small>
  - <small><strong>Revenue and Profit by Year:</strong> pivot table and chart summarising revenue and profit by year. </small>  
  - <small><strong>Product Revenue by Country:</strong> pivot tables and charts summarising product revenue by country. </small>  
  - <small><strong>Revenue by Age Group:</strong> pivot tables and charts summarising revenue by age group. </small>

### 📋 Dataset Structure

| Column Name        | Description                                                                   |
|--------------------|-------------------------------------------------------------------------------|
| Date               | Date of purchase (DD/MM/YYYY format)                                          |
| Day                | The day of the month of the transaction                                       |
| Month              | The month of the transaction                                                  |
| Year               | The year of the transaction                                                   |
| Customer_Age       | Age of the customer                                                           |
| Age_Group          | Age group of customer (Seniors, Adults, Young Adults and Youth)               |
| Customer_Gender    | Gender of the customer (M/F)                                                  |                                              
| Country            | Country of customer                                                           |
| State              | State of customer                                                             |
| Product            | Category of product ordered (bike, clothing, accessories)                     |
| Sub_category       | Subcategory of product ordered                                                |
| Unit_Cost          | Cost price of product ($)                                                     |
| Unit_Price         | Selling price of product ($)                                                  |
| Profit             | Shows profit per transaction (Revenue - Cost)                                 |
| Cost               | Shows total cost to the business per transaction (Unit_Cost x Order_Quantity) |
| Revenue            | Shows the revenue per transaction (Unit_Price x Order_Quantity)               |
  
