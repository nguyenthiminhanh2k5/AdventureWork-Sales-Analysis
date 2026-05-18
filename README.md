**# AdventureWork-Sales-Analysis
___________________________________________________________________________________________________________
📝 OVERVIEW**

Project Background: This report was conducted to build an interactive and dynamic reporting system (Dashboard) in Power BI to analyze sales performance during the 2010–2013 period. The study focuses on deeply evaluating the dual-channel distribution strategy (Internet Sales and Reseller Sales), product structure, customer demographics, and profitability trends, thereby proposing operational optimization solutions.

Scope of Implementation: Analyzing the entire historical transaction data of AdventureWorks from 2010 to the end of 2013, covering key markets including North America, Europe, and Oceania (Australia).
___________________________________________________________________________________________________________
**📊 DATASET**

Data Structure: The original dataset consists of 15 interconnected tables. This includes 2 core transactional tables (Fact tables): Internet_Sales and Reseller_Sales. The supporting tables (Dim tables) include: Customer, Employees, Geography, Sales_Territory, Products, Product_Subcategory, Product_Category, and Internet_Sales_Reason.

Data Processing: The entire process of data cleaning, transformation, and data integrity normalization was performed directly using Power Query prior to analysis.
____________________________________________________________________________________________________________
**⚙️ TOOLS & TECHNOLOGIES**

Power Query: Used for data connection, merging tables, expanding data fields, and removing duplicates.

Power BI: The primary tool applied for Data Modeling, Table Relationship Management, calculating measurement metrics using DAX, and designing interactive data visualization dashboards.
____________________________________________________________________________________________________________
**📊 DASHBOARD PREVIEW**
____________________________________________________________________________________________________________
**🔹 Dashboard 1: AdventureWorks Sales Report - Development Trends**

KPI Cards:
Total Quantity
Total Revenue
Total COGS
Total Gross Profit
% Profit Margin

Slicer: Channel Filter (Internet / Reseller)
Donut Chart: Share of Revenue by Channel (Internet vs. Reseller)
Bar Chart / Column Chart: ($) Total Revenue by Group in Internet Channel
Tree Map / Regional Bar Chart: ($) Total Revenue by Region in Internet Channel
<img width="1277" height="717" alt="image" src="https://github.com/user-attachments/assets/2ef011e9-f785-47a6-a4f2-3c642d47f898" />
<img width="1281" height="725" alt="image" src="https://github.com/user-attachments/assets/225c1b9a-de20-4876-a4f5-857239e85db8" />
**🔹 Dashboard 2: AdventureWorks Sales Report - Internet Sales Analysis**

KPI Cards:
Total Quantity (Internet)
Total Revenue (Internet)
Total Gross Profit (Internet)
% Profit Margin (Internet)

Key Influencers Visual: What influences Internet_Sales to Increase / Decrease
Top Segments / Breakdown Charts: * Income Range (Middle Income)
Sum of YearlyIncome
CommuteDistance
Tree Map / Regional Bar Chart: Revenue and Profit share by Region & Country (Southwest, Northwest, United Kingdom, Germany, France, Canada, etc.)
Donut Chart: Internet Sales by Marketing Reason / Other Reason
<img width="1282" height="723" alt="image" src="https://github.com/user-attachments/assets/83b9045c-0a56-4cf1-880e-679f03befa2f" />
**🔹 Dashboard 3: AdventureWorks Sales Report - Reseller Sales Analysis**

KPI Cards:
Total Reseller
Total Quantity
Total Revenue
Total Profit

Slicer: Filter by Year

Horizontal Bar Chart: Revenue by Category (Bikes, Components, Clothing)
Donut Chart / Pie Chart: Revenue by Business Type (Warehouse, Value Added Reseller, Specialty Bike Shop)
Geographical Bar Chart / Tree Map: Revenue by Country (United States, Canada, etc.)
Line and Stacked Column Chart: Revenue and Profit Margin by Top-6... (Trends over time)
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/4bcd97fa-c1e3-44c5-b728-6e8f94a745a6" />
____________________________________________________________________________________________________________
**📈 KEY INSIGHTS**
____________________________________________________________________________________________________________
### 📈 Overall Performance (2010–2013)
* **2010:** Revenue was low ($10.8M); Reseller dominated North American sales, but Internet Sales drove 80.58% of profits due to low COGS.
* **2011:** Revenue tripled ($32.54M) via wholesale spikes, though Reseller profit margins fluctuated due to dealer discounts.
* **2012:** Peaked at record revenue **($42.35M)** and maximum profit margins by achieving economies of scale.
* **2013:** Revenue fell to $24.12M due to proactive restructuring to cut inefficient resellers; Internet Sales secured the cash flow.

### 🌐 Internet Sales Channel
* **Long-tail Strategy:** Shifted from high-value premium Bikes (2010–2011) to multi-category Accessories/Clothing (2012–2013) to boost repeat purchases.
* **Logistics Freeze:** Halted online accessory sales in late 2012 to prioritize warehouse resources for the peak summer bike season in Australia.
* **Target Audience:** Bike buyers were high-income middle-aged adults (49–69); accessory/clothing buyers skewed toward commuting seniors and stylish youth.

### 🤝 Reseller Sales Channel
* **Batch Sales:** Used a seasonal wholesale distribution strategy (bulk shipping in Jan, Mar, May) to manage supply chain absorption.
* **Ordering Habits:** Resellers concentrated large-scale orders mid-week (Tuesday–Friday) and Sundays, with minimal activity on Mondays and Saturdays.
* **Sales Force Impact:** Senior sales staff (aged 45–60) generated 58.62% of initial launch revenue through personal networks before processes were standardized for younger teams.
____________________________________________________________________________________________________________
**🚀 Project Highlights**
Built an end-to-end data analysis workflow from raw Excel data
Applied data cleaning techniques using Power Query
Designed interactive and user-friendly dashboards in Power BI
Delivered actionable business insights from sales data
____________________________________________________________________________________________________________
**👤 Author**

Minh Anh Nguyễn Thị

Aspiring Data Analyst
Skills: Power BI, Excel, Data Analysis
