# Power BI Sales Dashboard: Analytics & Insights
### Short Description
This project features an interactive Power BI dashboard designed to analyze and visualize sales data for improved business decision-making. The dashboard provides comprehensive reporting on product, customer, and geographical sales trends, highlighting key performance metrics, growth opportunities, and actionable insights for stakeholders.


#### [DASHBOARD LINK](https://github.com/praveen4399/SALES-DASHBOARD/blob/main/SALESDASHBOARD.pbix)

### Tech Stack
•	**Power BI Desktop** – Main data visualization platform used for report creation.<br>
•	**Power Query** – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	**DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic. [Formula](https://github.com/praveen4399/SALES-DASHBOARD/blob/main/dax.docx)<br>
•	**Data Modeling** – Relationships established among tables to enable single-filtering and aggregation.<br>
•	**File Format** – .pbix for development and .png for dashboard previews.<br>

### Data Source

**The data used for this Power BI dashboard is sourced from Kaggle:<br>**
**Dataset**: [Superstore Sales Dataset]<br>
**Description**: Contains retail sales transactions including orders, products, customers, shipping details, sales, and profit over multiple years.<br>
**License**: CC0: Public Domain.<br>
**Note**: Accessing the dataset may require a free Kaggle account.<br>


### Features / Highlights

 #### KPI Tiles (Top Row on Each Page)
•	**KPIs included**: Total Products, Total Orders, Total Quantity, Total Sales, Total Profits, each with current year (CY), last year (LY) values, and % change.<br>
•	**Business Value**: These indicators provide an instant snapshot of business performance. Comparing CY vs LY helps users quickly assess growth areas and identify trends requiring management attention.<br>
•	**Key Insights**: Provides summary statements such as sales increase by 20%, profit growth by 10%, which allows quick business performance tracking.<br>

#### Sales Overview
•	**Monthly Sales Trends (Bar Chart)**: Shows the monthly breakdown of sales revenue, highlighting seasonality and high/low-performing months. This is critical for planning promotions, inventory, or resource allocation during peak or low-sales periods.<br>
•	**Monthly Performance (Combo Chart)**: Combines monthly sales and profit on dual axes to analyze whether increased sales translate to increased profit. Management can instantly spot months where efforts led to disproportionately higher profits or where margin improvement is needed.<br>
•	**Top 5 Customers / Products / Cities (Bar Charts)**: Reveals the customers, products, and cities contributing the most to the business. Decision-makers can use this to deepen relationships, optimize supply to high-demand areas, and focus on high-value products.<br>


#### Customer Sales
•	**New Customers (Bar and Line Combo)**: The bar shows yearly count of new customers; the line tracks the trend. Useful for understanding acquisition success and how it changes year over year.<br>
•	**Segments by Customers (Pie Chart)**: Displays proportion of customers by segment (Home Office, Corporate, Consumer). Helps in customizing product offerings and marketing strategies per segment.<br>
•	**Top 5 Customers by City (Bar Chart)**: Shows which cities are home to the most valuable customers, potentially guiding regional investments.<br>
•	**Monthly Performance by Customer (Bar List)**: Ranks customers by monthly sales and provides the top N contributors—useful for account-based marketing and retention efforts.<br>

#### Item Sales
•	**Products by Categories (Bar Chart)**: Highlights which product categories (e.g. Office Supplies, Technology, Furniture) are selling the most. Supports decisions about stock focus and marketing.<br>
•	**Sales & Profits by Category (Bar & Line Combo)**: Compares sales and profit simultaneously by category, helping understand which product lines are not just selling, but also yielding high margins.<br>
•	**Segments by Products (Pie Chart)**: Shows distribution of products sold by customer segment—useful for customizing sales strategies.<br>
##### To create an interactive parameter (field parameter) that allows users to switch between viewing:   <br>        
•	**Quantity by Product Name**<br>
•	**Sales by Product Name**<br>

1.	**Quantity by Product Name (Horizontal Bar Chart)**: Lists top products by quantity sold, making it easy to spot best-sellers and plan inventory accordingly. <br>

2.	**Sales by Product Name (Horizontal Bar Chart)**: Lists top products by quantity sold, making it easy to spot best-sellers and plan inventory accordingly<br>



#### Sales Orders

•	**Order Table (Tabular Visual)**: Provides a searchable, filterable list of all orders, with order details (ID, product, quantity, customer, date). Enables users to drill down for detailed operational insights, spot issues, or conduct audits.<br>


### Business Impact / Insights
•	**Revenue and Profit Growth**: The dashboard reveals a 20% increase in sales and 10% increase in profit, evidencing overall positive business health and successful sales strategies.<br>
•	**Operational Efficiency**: Insights into monthly and category trends help optimize inventory and streamline operations to match demand patterns.<br>
•	**Customer Retention & Expansion**: Tracking new and top customers by segment and city supports focused retention plans and identifies potential geographic expansion opportunities.<br>
•	**Data-Driven Decision Making**: The dashboard enables leadership to quickly identify strengths and weaknesses, prioritize actions, and measure progress against strategic goals.<br>

### [DEMO VIDEO](https://github.com/praveen4399/SALES-DASHBOARD/blob/main/salesdashboard.gif)




