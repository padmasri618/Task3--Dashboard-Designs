## 1. Objective
- The objective of this task is to design an interactive business dashboard using Tableau or Power BI based on a sales/financial dataset. The dashboard should help business stakeholders understand key metrics, trends, and performance insights effectively, enabling data-driven decision-making.

## 2. Report Structure
- The report/dashboard includes the following components:

- KPI Cards: Display total values like total sales, total profit, and growth percentage.

-Time Series Chart: Visualize sales over time for trend analysis.

- Categorical Analysis: Visuals to show sales/profit by card brand, region, and product.

- Filters/Slicers: Allow users to filter the data by card brand, category, or time period.

- Design Enhancements: Consistent color scheme, interactive elements, and background styling.

- Conclusion Section: Summarizes findings and key business insights.

## 3. Dataset Explanation
--File Used: cards_data.csv

- Source: Assumed to be a financial/card transaction dataset (e.g., from Kaggle).

## Key Columns:

-- Card Brand: Type of card used (e.g., Visa, MasterCard).

- Region: Geographic area of transactions.

- Sales: Revenue generated.

- Profit: Profit from sales.

- Date: Date of transaction (used for time series analysis).

- Discount: Discount applied.

- Product Name: Name of the product sold.

## 4. Visuals Used
-- Chart Type	Purpose
- KPI Cards	Show Total Sales, Total Profit, Total Orders
- Line Chart	Sales Trend Over Time
- Map (Optional)	Regional Sales Visualization
- Bar Chart	Sales by Card Brand
- Stacked Column Chart	Profit by Product Category/Brand
- Scatter Plot	Discount vs Profit Analysis
- Filter Slicers	Interactive filters for card brand, region
## 5.Bar Chart: Top Card Brands
  ![Top Card Brands by Issuance](https://github.com/user-attachments/assets/2697d294-e766-4271-be4b-0349fe421e48)

- Line Chart: New Accounts Over Time
  ![Monthly New Account Openings](https://github.com/user-attachments/assets/a859f92b-8341-4ff4-87fb-3ef8caf977d9)

- Filters: Card Brand, Has Chip, Card On Dark Web
![Distribution of Card Types](https://github.com/user-attachments/assets/6266d704-4c8a-4acf-a5d7-da52e3a5964b)

## 6. Insights, Patterns & Anomalies
--Insights:
- Top-Performing Card Brand: Certain brands (e.g., Visa) consistently lead in total sales and profit.

- Time-Based Trends: Sales are higher during certain months/quarters, indicating seasonal trends.

- High Discounts Reduce Profit: Scatter plot shows higher discounts often correlate with lower profits.

--Patterns:
- Geographic Trend: Some regions consistently perform better in both sales and profit.

- Consistent High-Sellers: Specific products contribute the most to profit repeatedly.

--Anomalies:
- Negative Profits: Certain high-discount products result in net losses.

- Sudden Spikes/Dips: In sales in specific months, possibly due to promotions or data quality issues.

## 7. Conclusion
--The dashboard effectively presents an interactive view of the business performance metrics. Through KPIs, trend analysis, and category-wise breakdowns, stakeholders can:

- Identify top-performing brands and regions.

- Understand how discounts impact profitability.

- Pinpoint seasonal trends and opportunities for promotion.
The insights derived from this dashboard can help optimize pricing strategies, product offerings, and regional focus for better profitability.

