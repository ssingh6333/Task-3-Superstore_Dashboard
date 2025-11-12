# Task-3-Superstore_Dashboard
This Power BI dashboard provides a comprehensive analysis of the Superstore Sales dataset. It highlights key business performance metrics such as Total Sales, Total Quantity Sold, and Total Profit, while also offering insights into customer behavior, geographic sales distribution, and shipping trends.

The dataset used in this task contains Superstore sales records, including fields such as:
Order Date, Ship Date
Customer Name, Segment, Region, State
Product Category & Sub-Category
Sales, Quantity, and Profit
The objective of this task is to clean the dataset and create an interactive business dashboard using Power BI.
| Cleaning Step              | Description                                                                                |
| -------------------------- | ------------------------------------------------------------------------------------------ |
| Removed duplicate rows     | Ensured no repeated transactions exist                                                     |
| Corrected date format      | Standardized mixed **`MM-DD-YYYY`** and **`MM/DD/YYYY`** to a single date format           |
| Checked data types         | Converted Sales, Quantity, Profit to **Whole/Decimal Numbers**, and Dates to **Date Type** |
| Removed unnecessary spaces | Trimmed text fields (Customer Name, Product Name, etc.)                                    |
| Ensured column consistency | Verified columns names and structure                                                       |
Step-2 : Dax Function
Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Quantity = SUM(Sales[Quantity])

Customer Count = DISTINCTCOUNT(Sales[Customer Name])

Step-3 : Data Visualization
| Visualization                                             | Purpose                                                                           |
| --------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **KPI Cards** (Total Sales, Total Profit, Total Quantity) | To display overall business performance at a glance                               |
| **Donut Chart – Customer Segment Distribution**           | Shows percentage share of Consumer, Corporate, and Home Office customers          |
| **Map / Filled Map – Customer Count by State & Segment**  | Displays geographical distribution of customers across states by business segment |
| **Bar/Line Chart – Customer Count by Ship Date**          | Shows shipping trends and daily order/customer volume                             |
Slicers added:

Order Date

Segment

Region / State

This makes the dashboard fully interactive.

Step 4: Dashboard Outcome
This dashboard helps in:*Understanding which segment has highest customer share. *Identifying high-demand regions and potential growth areas Tracking shipping activity patterns over time *Measuring overall sales and profit contribution
