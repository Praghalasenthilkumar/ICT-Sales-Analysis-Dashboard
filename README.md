# ICT-Sales-Analysis-Dashboard

1. Project Title / Headline

ITC Sales Analysis: Net Sales, Brand, Channel, and Customer Performance Dashboard

A two-page Power BI dashboard that tracks ITC food brand sales across India by brand, sales channel, region, payment method, customer segment, and state, with a drill-down view of brand-level profit and gross sales.

2. Short Description / Purpose

The ITC Sales Analysis Dashboard shows how net sales, gross sales, profit, and quantity sold developed over the period covered by the data, and where those sales came from. It helps users see which brands lead, how sales change month to month, which regions and states perform best, and how customer segments and payment methods contribute. It is intended for sales managers, brand managers, and business analysts.

3. Tech Stack

The dashboard was built using the following tools and technologies:

Power BI Desktop: Main data visualization platform used for report creation.
Power Query: Data transformation and cleaning layer for reshaping and preparing the data.
DAX (Data Analysis Expressions): Used for calculated measures such as net sales, gross sales, profit, profit margin, and customer counts.
Data Modeling: Relationships among sales, brand, product category, customer, geography, and date tables to enable cross-filtering and aggregation.
Map Visual: Power BI map visual used for state-wise sales across India.
File Format: .pbix for development and .png for dashboard previews.
4. Data Source

Sales transaction records for ITC food brands across Indian states and cities, covering net sales, gross sales, profit, quantity sold, brand, sales channel, region, state, city, payment method, customer segment (Mass, Premium, Value), customer status (new or returning), category, and day of sale.

https://ww .com/datasets/rahul149/ictsales

5. Features / Highlights
Business Problem

Sales and brand teams need to know which brands drive revenue, which regions and states are under-performing, which payment methods and customer segments matter most, and how sales change over time. Without a single view, these answers are spread across separate reports.

Goal of the Dashboard
Track net sales, gross sales, profit, and total quantity sold.
Compare brand performance on net sales, profit, and gross sales.
Identify strong and weak regions, states, and cities.
Understand the mix of customer segments, new versus returning customers, and payment methods.
Spot which days of the week generate the most sales.
Walkthrough of Key Visuals

ITC Sales Analysis 1 (overview page)

KPI cards: Net Sales (8.55M), Gross Sales (9M), Total Profit (2.72M), Total Quantity (68K).
Net Sales Over Time: Monthly line chart. April is the highest month at 0.97M, and sales fall sharply from October onward, reaching 0.43M in December.
Brands Wise Sales: Bar chart with Aashirvaad well ahead at 4.1M, followed by Sunrise (1.0M), Sunfeast and YiPPee! (0.9M each), Fabelle (0.8M), Bingo! (0.5M), and Candyman (0.3M).
Sales Channel Wise Performance: Bar chart by region: South (3.5M), West (1.9M), North (1.8M), and East (1.3M).
Payment Method Wise Net Sales: Donut chart with Net Banking (1.82M, 21.35%), Debit Card (1.78M, 20.88%), Credit Card (1.69M, 19.8%), UPI (1.64M, 19.22%), and Cash (1.6M, 18.75%).
Day Wise Sales: Treemap with Friday highest (1.42M), followed by Monday and Wednesday (1.24M each), Tuesday (1.20M), Saturday (1.18M), and Thursday and Sunday (1.13M each).

ITC Sales Analysis 2 (detail page)

States and Cities: Slicer list for filtering by state and city, such as Delhi, Gujarat (Ahmedabad), Karnataka (Bengaluru), Kerala (Kochi), Maharashtra (Mumbai and Pune), and Odisha (Bhubaneswar).
State Wise Sales: Map of India shaded by sales value by state.
Brand table: Net Sales, Profit, and Gross Sales for each brand, with totals of 85.45 lakh net sales, 27.18 lakh profit, and 94.27 lakh gross sales. Aashirvaad leads with 41.47 lakh net sales and 13.13 lakh profit.
Sales by Customer Segment: Mass (4.87M, 56.94%), Premium (1.92M, 22.47%), and Value (1.76M, 20.59%).
Customer Status: Returning customers account for 5.82M (68.08%) and new customers for 2.73M (31.92%).

Slicers: Payment, Channel, State, Year, Customer Segment, Region, Brand, and Category filter both pages. A Clear All button resets all filters.

Business Impact & Insights
Brand concentration: Aashirvaad generates about half of total net sales, so it is the main revenue driver and a key risk if its performance drops.
Strong retention: Returning customers make up about 68% of sales, which suggests loyal buyers. New-customer acquisition still adds about a third of revenue.
Mass market focus: The Mass segment contributes nearly 57% of sales, so mass-market pricing and availability matter most.
Regional gap: South leads by a wide margin, at about 3.5M compared with 1.3M in East. Growth efforts could target East and North.
Declining trend: Net sales fall from 0.97M in April to 0.43M in December, with a sharp drop after September. This needs investigation before the next planning cycle.
Weekday pattern: Friday is the strongest sales day, which can guide promotions, staffing, and stock planning.
Payment mix: Payment methods are evenly spread (about 19% to 21% each), so no single method dominates, and checkout options should stay broad.
Business value: Supports decisions on brand investment, regional targets, customer retention programs, and weekly promotion timing.
How to Use
Open ICT_Sales_Analysis.pbix in Power BI Desktop.
Use the slicers (Payment, Channel, State, Year, Customer Segment, Region, Brand, Category) to filter the view.
Switch between ITC Sales Analysis 1 and ITC Sales Analysis 2 using the page navigation at the top.
Select a state or city in the States and Cities list to update the map and tables.
Click Clear All to reset all filters.
Known Issues
The two Profit Margin cards both show 159.81K, which looks like a formula or card binding error. Based on the other figures, the profit margin should be about 31.8% (2.72M profit on 8.55M net sales).
The Net Sales Over Time x-axis is not in calendar order (for example, April appears before March). Sorting the month column by month number will fix this.
The "Sales Channel Wise Performance" visual shows regions (South, West, North, East), so its title may need updating.
Author

Praghala A S - praghalasenthilkumar@gmail.com
