# Blinkit-Sales-Performance-Analysis---Power-BI-Dashboard
# Project Overview
This Power BI dashboard analyzes Blinkit’s sales performance, customer satisfaction, and inventory distribution to identify optimization opportunities. The project leverages KPIs and interactive visualizations to uncover trends in sales, product categories, outlet performance, and customer ratings. The dataset used contains grocery sales information with details about products, outlets, and sales performance.

# Need for insights
Blinkit (a quick e-commerce platform) needs data-driven insights to:

- Optimize sales strategies by product type, fat content, and outlet characteristics.
- Improve customer satisfaction by analyzing ratings and demand patterns.
- Enhance inventory distribution based on geographic and outlet-level performance.

# Key Performance Indicators (KPIs)

The key performance indicators I used for this project was: 
- Total Sales: Overall revenue generated.
- Average Sales: Revenue per transaction.
- Number of Items Sold: Total products sold.
- Average Rating: Customer satisfaction score.

# Business & Chart Requirements

1.	Total Sales by fat content:
- Objective: analyze the impact of fat content on total sales
Additional KPI metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
- Chart type: Donut chart.

2.	Total Sales by item Type:
- Objective: Identify the performance of different items types in terms of total sales.
- Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
- Chart type: Bar Chart.

3.	Fat Content by outlet for Total sales:
- Objective: Compare total sales across different outlets segmented by fat content.
- Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
- Chart Type: Stacked Column Chart.

4.	Total Sales by outlet Establishment:
- Objective; Evaluate how the age or type of outlet establishment influences total sales.
- Chart type: line chart.

5.	Sales by outlet size
- Objective: Analyze the correlation between outlet size and total sales.
- Chart Type: Donut/pie chart.

6.	Sales by Outlet location:
- Objective: Assess the geographic distribution of sales across different locations.
- Chart Type: funnel Map.

7.All metrics by outlet type:
- Objective: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, average Rating) broken down by different outlet types.
- Chart type: Matrix Card.

# The Project Steps I took to complete the prject

1. Requirement Gathering: Defined KPIs and business goals.

2. Data Walkthrough: Explored raw datasets (sales, outlets, ratings).

3. Data Connection: Integrated CSV/Excel/API data into Power BI.

4. Data Cleaning: Handled mostly Some inconsistencies in labeling ("low fat" vs "Low Fat" vs "LF")

5. Data Modeling: Created relationships (e.g., Sales[Outlet_ID] → Outlets[ID]).

6. DAX Calculations: Built measures for KPIs (e.g., Total Sales = SUM(Sales[Revenue])).

7. Dashboard Layout: Designed intuitive tabs (Sales, Outlets, Customer Insights).

8. Visualizations: Developed charts per business requirements.

9. Report Finalization: Added filters, tooltips, and dynamic titles.

10. Insights Generation: Derived actionable conclusions (see below).

# Insights 
After analyzing the data, here are the key insights:
1. Product Performance
- Top Selling Categories: Fruits & Vegetables (most frequent item type), followed by Household products and Frozen Foods

- Fat Content Distribution:

- Low Fat products dominate (72% of items)

- Regular fat products account for 25%

- High Visibility Items: Items with visibility > 0.15 tend to have higher sales (average $195) compared to low visibility items (average $135)

2. Outlet Performance
Outlet Types:

- Supermarket Type1 is most common (60% of outlets)

- Grocery Stores have the lowest average sales ($125 vs $165 for supermarkets)

Outlet Size Impact:

- Medium-sized outlets generate the highest average sales ($158)

- Small outlets have lowest average sales ($142)

Establishment Year:

- Newer outlets (established after 2015) perform slightly better (average $152) than older ones ($145)

3. Sales Patterns
- Average Item Weight: 13.5 units (with some missing values)

- Sales Distribution:

- Average sale: $150.42

- Top 10% items account for 22% of total sales

- Bottom 10% items account for just 6% of total sales

Rating Consistency: Most items (95%) are rated 4.5-5.0, suggesting potential rating inflation

4. Recommendations
- Inventory Optimization: Focus on high-performing categories (Fruits & Vegetables, Household)

- Standardize Labeling: Clean up fat content categories for consistent reporting

- Outlet Strategy: Invest in medium-sized supermarket formats which show best performance

- Pricing Strategy: Investigate the negative visibility-sales correlation - potentially adjust pricing for high-visibility items

- ata Quality: Address missing weight values (about 8% of records) for better analysis

5. Potential Growth Areas
- Expand high-performing item types in top-tier locations

- Consider reducing low-performing SKUs (especially in the "Others" category)

- Explore why newer outlets perform better and replicate those success factors

# How to Use This Dashboard
1. Download the .pbix file and open in Power BI Desktop.

2. Use slicers (e.g., date range, outlet type) to filter data dynamically.

3. Hover over visuals for tooltips with granular metrics.

Final project view (screenshot)
![2025-06-04 20 11 53](https://github.com/user-attachments/assets/7029769e-4b92-4954-9cc5-3aa948c5ac08)

1. Data Sources: Blinkit sales records, outlet metadata, customer ratings.
2. Tools Used: Power BI, Power Query, DAX.

Feel free to fork the project and try it yourself dont for forget to like
