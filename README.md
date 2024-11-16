# Forggith Pharmaceuticals Report

# ![Logo](https://github.com/user-attachments/assets/48043b86-a06e-45e5-a7ea-daed9eeba037)

# Introduction
During my one-month Power BI Developer internship with Foresight BI & Analytics, I worked on a comprehensive project for Forggith Pharmaceuticals, a Germany-based pharmaceutical manufacturing company. Forggith specializes in producing medical drugs distributed to consumers through a network of distributors. This project focused on creating an interactive Power BI report to analyze performance across different sectors, categories, and time periods. The goal was to provide actionable insights for various stakeholders: Sales Representatives to evaluate their performance and optimize marketing activities, Team Managers to monitor and strategize team operations, and the Executive Team to track revenue trends and assess alignment with organizational targets for informed medium- to long-term strategic planning.

# Problem Statement
# Sales Performance
1.Total Revenue
2.Total Revenue Year To Date (YTD)
3.Total Revenue Previous Year YTD
4.Total Revenue Same Period Last Year(SPLY)
5.Total Target
6.Total TargetYTD
7.Actual Revenue Performance Previous Year YTD vs Target Previous Year YTD
8.Actual Revenue Performance YTD vs Target YTD
9.Revenue Month on Month Percentage Change
10.Revenue Distribution by Location
11.Revenue by Channel
12.Revenue by Product Class

# Marketing Performance
1.Revenue Achieved vs Revenue Target
2.Volume Achieved vs Volume Target
3.Actual Revenue by Sales Representative
4.Target Revenue Achievement% by Sales Representative
5.Actual Volume by Sales Representative
6.Target Volume Achievement by Sales Representative
7.Actual Revenue Achievement by Sales Team
8.Revenue and Volume Achievement by Product.

# Skills/Concepts Demonstrated
The following Power BI features were incorporated:

Power Query for transformation
Bookmarking
DAX
Quick measures
Page navigation
Modelling
Filters
Tooltips
Button

# Data Sourcing
The data was sourced from the Foresight BI & Analytics team since it was an internship program.

Forggith-Pharmaceuticals-Report database tables - PharmDatasets and PharmTargets The following tables were selected from the dataset to be used for the analysis

1.Channel Table
2.Employees Table
3.Location Table
4.Products Table
5.Sales Table
6.Subchannel Table
7.Targets Table

# Pharm Datasets
# ![image](https://github.com/user-attachments/assets/9ac200bc-8c14-4e43-9b1d-f9bbcafcb7c3)

# Pharm Targets
# ![image](https://github.com/user-attachments/assets/7792d5e0-89f1-4dfa-8e3f-77014addf6bc)

# Data Transformation
For all the tables, the first rows were changed to become Headers.

In the Sales Table, the data type for the "MonthYear" column was changed to Date. I also appended queries for the "2023-2025" sales table to the "2022" sales table and named it "Sales"
# ![image](https://github.com/user-attachments/assets/71fa8e0d-ad5c-4d7f-9e6c-e7bcea37e615)

In the Targets Table, I unpivoted the year columns, then I merged the month and the year column together. I also changed the data type to Date and renamed it as "Date"
# ![image](https://github.com/user-attachments/assets/c21b9f0c-a55b-4baf-9907-ec3bc83d78c4)

# Data Modelling
The model is a star schema. There are 5-dimension tables and 2 fact tables. The dimension tables are all joined to the fact tables with a many-to-one relationship.

# Auto Model                                                                                                            
# ![image](https://github.com/user-attachments/assets/6661dccd-d345-4a79-8b1c-30cff646008b)                             

# Adjusted Model
# ![image](https://github.com/user-attachments/assets/15c59141-8496-44de-8100-600d375dad21)

The model is a star schema. There are 5-dimension tables and 2 fact tables. The dimension tables are all joined to the fact tables with a many-to-one relationship.

# Visualization
The report comprises of 3 pages:

1. Overview (Home)
2. Sales Report
3. Marketing Report

You can interact with the report [here]([https://dashboard.url](https://app.powerbi.com/view?r=eyJrIjoiOWNmYTc5MjMtMTYzNC00NmE2LWExZTQtZmM5MWQ1ZmZjNjBmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9))

I also incorporated tooltips for better insights.
# ![image](https://github.com/user-attachments/assets/e154e5af-2ebf-49ce-807f-76c189b49646)

# Analysis
# Overview/Home Page:
# ![image](https://github.com/user-attachments/assets/6d55c33e-9200-44c1-88ff-ff91eaaeac80)


Has a Date filter that filters through 2022 - 2025.
The three tabs at the top are buttons with hovering effects and each navigates through to the pages with similar name.
Total of 27 million products were sold.
Total revenue generated was $11.12 billion 💰
Total target was $8.45 billion.

# Sales Report Page:

# ![image](https://github.com/user-attachments/assets/d5353f28-d580-4fcc-8850-9be435674761)

This page is organized by Team, Year, Quarter, and Month 🗓️.

It shows 4 key performance indicators (KPIs):

Total Target
Total Products
Volume Sold vs Target Volume
Total Revenue vs Target
The page also includes charts that display:

Revenue by Product Class
Revenue by Channel
Revenue Distribution by City
Monthly Revenue Percentage Change
Revenue vs Target for the Previous Year-to-Date (PYTD)
There are a total of 240 products.

# Marketing Report Page:

# ![image](https://github.com/user-attachments/assets/9902d002-3352-4dbd-8910-a22e83cd6e22)

This page is organized by Product Category, Team, Year, Quarter, and Month 🗓️.

It shows 4 key performance indicators (KPIs):
Total Customers
Total Distributors
Volume Sold vs Target Volume
Total Revenue vs Target

The page also includes charts displaying:
Top and Bottom % of Products by Performance
Revenue Performance by Team
Performance by Sales Representatives
There are a total of 551 customers 🧑‍🤝‍🧑 and 16 distributors.

# Conclusion / Insights
The Analgesics Product Class yielded the highest revenue of $2.2bn while the Antimalarial class yielded the lowest revenue of $1.4bn.
Ionclotide drug yielded the highest revenue of $262k as product sold while Diaxolol yielded the lowest of $72K in total.
2023 gave the highest revenue of about $0.9bn when compared to its yearly target as against other years.
Distribution/Sales to Pharmacies yielded more revenue of 52.9% as compared to that of the Hospital channel.
The Delta team showed highest performance in all years generating a total revenue of $3.43bn 👍 while the Alfa team showd lowest performance of $2.42bn.
In 2022, Anne Wu performed best. In 2023, Abigail Thompson perfomed best. In 2024, Jimmy Grey performed best and in 2025, Stella Given performed best. Overall, Abigail Thompson yielded the most revenue of $929.43m ✨

# Recommendation
I recommend expanding distribution and sales beyond Europe, as this will favour sales of other classes more, especially the antimalarial drugs.
Best performing teams should be given higher bonuses as this will make other teams perform better in future years to come.
Sales Representatives seen to be performing well should be also be given bonuses, or better still have their salaries increased and should also be considered for promotions.

# ![image](https://github.com/user-attachments/assets/f91f2308-8a2b-40bd-a217-1c2b21a31729)


