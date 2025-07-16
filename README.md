📊 Sales Analysis Dashboard – Power BI Project
An interactive Power BI dashboard that provides deep insights into sales, profit, quantity sold, promotions, and customer behavior across time periods and product categories. This project is built to help stakeholders make informed, data-driven business decisions.

🧭 Project Objectives
This project aims to deliver a comprehensive view of business performance through the following:

📦 Identify Top & Bottom 5 Products by Sales, Profit, and Quantity

📈 Analyze Sales Trends over different time periods (daily, monthly, quarterly, annually)

💰 Explore the relationship between Profit and Net Sales

🧮 Compare performance across two selected time ranges

🎯 Visualize Average Discount offered under various promotion types

🏙️ Track Sales by City

🗃️ Provide detailed order-level drilldown with filters for Customer, Product, Date, and Promotions

🏗️ Data Model (Star Schema)

Fact Table:

Order details (CustomerID, ProductID, PromotionID, Net Sales, Profit, Units Sold, etc.)

Dimension Tables:

Dim Product: Product info (Name, Line, Price)

Dim Customers: Customer info (City, State, Contact)

Dim Promotion: Promotion type and discount

Date Tables: Separate date dimensions for different comparisons

Measure Table: Derived metrics like Quantity Sold

📁 Key Features in the Dashboard
🔝 Top/Bottom 5 Products Analysis
Metric	Top 5	Bottom 5
Sales	Apple iPhone 14, MacBook Air, Sony Bravia TV	Colgate, Dove, Nivea
Quantity	iPhone 14, Raymond Suit, Zara Shirt	Borosil Set, FabIndia Kurta
Profit	iPhone 14, MacBook Air, Sony Bravia	Tupperware, L'Oreal, Dove


🗓️ Trend Analysis & Period Comparison
Tracks weekly and monthly sales spikes

Compare two custom time periods using slicers for:

Total Sales

Profit

Quantity Sold



🌍 Geographic & Promotion-Based Insights
Sales by City using interactive map

Analyze promotion effectiveness via average discount


📋 Order-Level Details with Filters
Drill down into each transaction with slicers for:

Product Name

Promotion Category

Customer Name

Date


🧪 Tools Used
Tool	Purpose
Power BI	Data modeling, DAX measures, dashboard creation
DAX	Calculated columns and KPIs
Excel/CSV	Source data files
Star Schema	Optimized data structure for BI

📂 Project Structure
bash
Copy
Edit
sales_analysis_dashboard/
├── 1.png                  # Top/Bottom products visualization
├── 2.png                  # Trend, map, and profit-sales relationship
├── 3.png                  # Date-based comparison
├── 4.png                  # Raw order table visual
├── er_model.png           # Data model (ER diagram)
├── Project Requirements.pptx  # Scope and use cases
└── README.md              # Project overview
🔍 Key Learnings
Creating optimized data models for BI tools

Designing interactive visuals with slicers and filters

Using DAX for complex KPI derivation

Business storytelling with multi-layered insights

✅ How to Use
Open the .pbix file in Power BI Desktop. Use slicers to explore time-based and categorical insights.

📬 Contact
Made by Anshuman Bansal
🔗 GitHub: @anshumanbansal23
