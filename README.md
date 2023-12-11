Documentation of Chocolate Sales Data: Interactive Dashboard Creation

Introduction
This documentation provides an overview of the project focused on creating an interactive dashboard to analyze sales data. The dashboard was built using Excel, Power Pivot, and advanced Excel functions. The primary objectives were to enable data-driven decision-making and enhance data visualization for our Project Dataset.

Business Understanding
We believe that a business is a powerful force that can offer valuable products and services to customers, while generating revenue and profit in the process. With every industry comes unique challenges and opportunities, but we're confident that with the right insights and data analysis, any business can succeed in a competitive landscape. We're enthusiastic about helping businesses make informed decisions that will lead to thoughtful growth and positive outcomes.
I've created an interactive dashboard that helps me analyze sales data, a crucial aspect for many businesses. By examining sales data, I can gain valuable insights into how products are performing, identify profitable regions, and assess the impact of teams on overall revenue and profit. This dashboard is especially helpful in tackling common business hurdles and finding effective solutions. Let's take a closer look at how it can assist me in achieving this.
•	Performance Analysis: The dashboard provides a comprehensive view of our sales and profit performance. We can quickly assess the overall sales, profit, and other key metrics using KPI tiles. This information helps us to identify if our business is meeting its targets and where it might need to catch up.
•	Product Category Insights: Category-wise sales information allows us to dive deeper into our product performance. We can identify which product categories are the most profitable and which need attention. This insight can guide product development and marketing strategies.
•	Team-Based Performance: Understanding the performance of different teams is crucial. The "Team-Based Performance Metrics" section shows how each team contributes to sales and profit. This can help recognize top-performing teams and address any underperforming issues.
•	Product-Based Insights: The section on product performance details provides a granular view of individual products. We can identify top-selling products, analyze their profitability, and make decisions regarding inventory management and marketing efforts.
•	Visualizations: Using a gauge chart and other visualizations makes it easier to grasp key insights at a glance. Visual data representation helps in quickly spotting trends or anomalies.
•	Interactive Slicers and Filters: Slicers and filters enable us to customize the dashboard view based on specific criteria. For example, we can focus on sales data for a particular region, category, or team. This flexibility allows us to answer specific questions and address issues more effectively.
•	Data Validation and Sparklines: The dynamic table with data validation and sparklines for the last 28 days' performance provides us with a tool for monitoring short-term trends. We can quickly assess how sales and profit are trending in recent weeks and take action accordingly.
•	Sorting Options: The sorting options in the dashboard help you prioritize data based on different factors like sales, profit, and profit percentage. This can be valuable when deciding on resource allocation or identifying areas needing improvement.
•	Data Modeling and Advanced Functions: Using Power Pivot and advanced Excel functions ensures that our data is well-structured and that we can perform complex calculations and analysis. This is essential for accurate decision-making.

In summary, this interactive dashboard is equipped with the tools to:
•	Monitor overall business performance.
•	Identify strengths and weaknesses in product categories and teams.
•	Make data-driven decisions about product development, marketing strategies, and team management.
•	Track short-term trends for timely actions.
•	Customize data views for specific needs.

By using this dashboard effectively, we can address everyday business challenges, make informed decisions, optimize operations, and ultimately grow our business while ensuring profitability. It serves as a valuable tool for analyzing your sales data comprehensively and turning that analysis into actionable insights.
Dashboard Overview
The interactive dashboard comprises several key components, including:
    •    Region-Wise Sales and Profit Analysis
    •    Sales by Product Category
    •    Team-Based Performance Metrics
    •     Product-Based Performance Metrics
    •     Visualizations (Gauge Chart)
    •     Interactive Slicers and Filters

Data Sources
Sales Data
Source: Kaggle
Data Transformation: I am using a clean dataset for this project. However, I have to remove some values from a dataset unsuitable for visualization, introduce bias into statistical calculations, and use custom formatting for the Date and Amount Column.
Data Model
The project involved creating a data model in Power Pivot. Critical aspects of the data model include:
•  Relationship establishment between tables using one-to-many, many-to-one, one to one concepts.
 

Note: The calculation worksheet is the base of the dashboard where we prepare our data and use the power of pivots and the advanced function of Excel.
Dashboard Features
On the left side of the dashboard, I created 6 KPI Tiles. Details Are below: -
   

Total Sales: - In This Tile, Bold Blue Fonts represent the complete sale of All products sold by all teams.
Selected Category-Wise Sales: - On the upper side of the tile, we represented the category-wise sales, which we will choose in the slicer
Mom % or Month on Month changes: - Percentage of sales month on month change by the latest month versus the previous month.

Boxes, shipments, cost, profit, and profit percentage all these tiles work on the same concepts as the sales tile.

  	   		
The Highlighted Country Map represents the highest Sales or Profit, which is selected in the sort option.

All other five tiles work on the same concepts as the first tile, which is explained.

The bubble title contains the team name with the team’s Total Sales and Profit Value


In the dashboard's middle section, I have included a bubble chart that matches the dashboard's formatting. The highlighted Bubble indicates the chosen team, selected from the "Pick a Team" option in the bottom bar.





I have generated a dynamic table below the bubble chart which presents data related to salespersons, sales, profit, and profit percentage. Moreover, I have added a data validation list in an extra column that offers several options. This feature facilitates us to conveniently review sales, boxes, shipments, and shipping status of the last 28 days with the help of a sparkline column. I use conditional formatting for alternate row shading and profit icons in this table. A blue horizontal line has also been added to delineate the table area.
I added a sorting option to the bottom bar of the table. If we sort by sales, the table will be sorted in ascending alphabetical order. If we select other options such as sale, profit and profit percentage, it will be sorted in descending order based on the value.

The dashboard's right side displays product performance details. I used a gauge chart on the upper section, created with a donut chart since Excel lacks that option.

 					 
Gauge Chart							    Slicer
The gauge chart displays the performance of all three categories chosen by the slicer. The chart label highlights each category's total profit and sales, and this applies to all three categories.
Slicers are essential in dashboards with multiple product categories. They allow us to customize visualizations by category.
 

The dashboard's right side displays a table with category-wise product names, sales, boxes, shipments, profit %, and last 28 days' performance of Sales, Shipments, Shipping status, and Boxes column with sparklines at the bottom. The yellow highlighted area shows products in the selected category.
In the bottom bar, I have also sorted options as we see in the previous table, and we have one another to turn on/off for the profit indicators.
To create a dynamic dashboard, I employed various advanced Excel functions and techniques such as pivot tables, measures within pivot tables, XLOOKUP, INDEX, MATCH, XMATCH, CHOOSE, SUMIFS, COUNTIF, COUNTIFS, MOD, IF-ELSE statements, conditional formatting, data validation, named ranges, cell references, charts, graphs, sparklines, data modeling, connections, formatting, custom formatting and text functions. These functions are commonly used in calculation worksheets.
Thank You
Nitesh Adwani
