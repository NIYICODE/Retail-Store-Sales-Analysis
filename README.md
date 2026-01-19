# **Sales Performance Analysis for DTLM Retail Using Excel**

## **Project Overview**
DTLM Retail operates across multiple regions, selling diverse products to a national and international customer base. The Sales Director requested a structured analysis of store performance to identify revenue drivers, high-performing products, and sales team efficiency. This project translates raw transactional and operational data into actionable insights using Excel’s advanced data modeling, reporting, and visualization capabilities.


## **Purpose**
**Primary Goal:** Provide a clear, data-driven view of sales performance across products, stores, and sales teams.  

**Secondary Goal:** Identify revenue trends, product and sales team performance, and key metrics that influence profitability for strategic decision-making.

## **Technical Stack**
- **Microsoft Excel:** Pivot Tables, Charts, Data Modeling  
- **Power Query:** Data cleaning, table merging, and transformation  
- **Excel Formulas:** SUMIFS, VLOOKUP, INDEX–MATCH for calculations  
- **Visualization:** Interactive charts and dashboard design


## **Data Source**
The project utilized multiple interconnected datasets:

| Table | Key Columns |
|-------|------------|
| **Sales** | Order Number, Order Date, Sales Channel, Currency, Sales Team Index, Store Index, Product Index, Order Qty, Unit Price, Unit Cost, Revenue, Profit |
| **Products** | Product Index, Product Name, Product Category |
| **Store Locations** | Store Name, County, State Code, State, Longitude, Latitude, Area Code, Population, Households, Median Income, Land & Water Area, Time Zone |
| **Sales Team** | Team Index, Sales Team, Region |



## **Analytical Narrative & Key Questions**

### **Business Problem**
The Sales Director needed clarity on performance metrics, revenue generation, and key product and team contributions. Without structured analysis, identifying high-value products, efficient sales teams, and regional revenue drivers was difficult.

### **Analytical Questions**
1. What is the revenue and profit per order?  
2. Which were the top 2 revenue-generating products in January?  
3. Which sales team generated the most revenue from Decoratives in March?  
4. Which metrics correlate with revenue at the state level?  
5. How do store locations, population, and demographics influence sales?



## **Data Preparation & Modeling**
- **Data Cleaning:** Used Power Query to remove inconsistencies and missing values.  
- **Table Merging:** Integrated multiple tables (Sales, Products, Store Locations, Sales Team) to create a unified dataset.  
- **Relationships:** Established data modeling relationships between tables to enable accurate calculations and PivotTable reporting.  
- **Metrics Engineering:** Calculated revenue and profit per order and aggregated by product, team, and state.



## **Reporting & Visualization**
- **Pivot Tables:** Generated reports for orders, products, sales teams, and regional metrics.  
- **Charts & Visuals:** Created line charts, bar charts, and heatmaps to highlight revenue trends, top products, and team performance.  
- **Dashboard:** Consolidated key insights into an interactive Excel dashboard, emphasizing revenue, profit, and product/team performance.



## **Business Impact & Insights**
- **Revenue Drivers:** Identified products and time periods contributing the most revenue.  
- **Team Performance:** Highlighted high-performing sales teams and areas for improvement.  
- **Regional Insights:** Discovered correlations between revenue and store demographics, guiding expansion and marketing strategy.  
- **Decision Support:** The interactive dashboard allows leadership to monitor sales, evaluate strategies, and make data-driven decisions.


## **Key Takeaways**
- Pivot tables and dashboards effectively translate raw sales data into actionable insights.  
- Integrating multiple datasets provides a holistic view of performance across products, teams, and regions.  
- Revenue, profit, and product performance metrics highlight actionable opportunities for sales optimization.  
- Data modeling enables repeatable, scalable reporting for ongoing decision-making.

![Dashboard]("sales report dashboard.png")
