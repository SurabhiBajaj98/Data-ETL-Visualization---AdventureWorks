## Data-ETL-Visualization-AdventureWorks
A comprehensive analysis of AdventureWorks sales data for 2020-2022, using Power BI

### Project Objective:
Help executives tailor their marketing strategies on the basis of the sales and profit trend in the past 2+ years, the products in focus, the customer profile and the country contributing to maximum orders.

### Dataset Used:
-  <a href="https://github.com/SurabhiBajaj98/Data-ETL-Visualization---AdventureWorks/blob/main/AdventureWorks%20Sales%20Data%202020.csv"> Sales 2020 </a>
-  <a href="https://github.com/SurabhiBajaj98/Data-ETL-Visualization---AdventureWorks/blob/main/AdventureWorks%20Sales%20Data%202021.csv"> Sales 2021 </a>
-  <a href="https://github.com/SurabhiBajaj98/Data-ETL-Visualization---AdventureWorks/blob/main/AdventureWorks%20Sales%20Data%202022.csv"> Sales 2022 </a>

### Visualization Goals:
1. Establish KPIs - Total revenue, profit, orders, return rate, recent month's numbers vis-a-vis target
2. Top 10 products by orders - drill through feature to give a view on metrics & profit if price adjusted
3. Customer profiling, top 100 customers, no. of unique customers and revenue per customer

###  Process:
1.	Understand the data – spent time on familiarizing myself with the dataset
2.	Folder extracted for sales data – ensured column and tab names for both sheets were uniform for smooth extraction
3.	Transformed the data – corrected data type and checked column quality to fix ‘errors’/ replace missing values, if any
4.	Standard naming convention, disabling refresh for static data like product and customer details
5.	Created relationships between fact and dimension tables , categorized state/country/address likewise to visualize them on a map
6.	Created a separate table for measures for organization
7.	Decided a uniform theme, font and background for the dashboards 

### Dashboard:

![image](https://github.com/user-attachments/assets/00d1ba6b-c904-4c7c-9e6b-7b70cc18c62a)
![image](https://github.com/user-attachments/assets/76e89fd8-a828-45f4-9943-9c6a736ac4cc)
![image](https://github.com/user-attachments/assets/48080f0d-15d9-45c3-9c40-5f93af4cb1c5)

- Snip 1: Executive Dashboard
- Snip 2: A drill through product details dashboard ( any product from executive dashboard can be selected and the details will get populated)
- Snip 3: Customer profiling

### Top Insights:
1. Revenue has increased by > 45% in 2021 vis-a-vis 2020
2. Water Bottle 30 Oz is the most ordered product among all 3 categories
3. It has fallen short on all 3 KPIs (profit, revenue, orders) for the current month vis-a-vis the target
4. However, total revenue for June 2022 has increased by 3% from previous month
5. Sports helmet has the highest return rate of > 3%
6. In clothing category, Logo Caps are the highest ordered
7. Maximum orders come from the U.S.

### Note:
Only Sales dataset has been uploaded. 



