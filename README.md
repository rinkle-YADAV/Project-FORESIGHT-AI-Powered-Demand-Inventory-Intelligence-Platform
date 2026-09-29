# Project-FORESIGHT-AI-Powered-Demand-Inventory-Intelligence-Platform
Project FORESIGHT is an AI-powered Demand &amp; Inventory Intelligence Platform that combines Python, SQL, Machine Learning, and Power BI to forecast demand, identify stockout and overstock risks, analyze sales trends, and generate actionable business insights through an interactive 12-page dashboard.

# 🔮 Project FORESIGHT

### AI-Powered Demand & Inventory Intelligence Platform



---

## 📌 Project Overview

**Project FORESIGHT** is an AI-powered demand forecasting and inventory intelligence platform designed to help retail businesses make data-driven inventory decisions.

The platform combines data analytics, machine learning, and business intelligence to forecast demand, identify potential stockouts, detect excess inventory, and generate actionable business recommendations.

It transforms raw retail data into meaningful insights through an interactive **12-page Power BI dashboard**, helping businesses understand sales patterns, optimize inventory levels, and plan future demand.

### 🎯 Project Objectives

* Forecast future demand and revenue to support purchasing decisions.
* Identify products at risk of stockouts before inventory runs out.
* Detect overstocked and slow-moving products.
* Analyze sales trends across products, categories, seasons, and customer segments.
* Provide actionable, data-driven recommendations for inventory optimization.

---

## 🚀 Key Features

### 📊 1. Executive Dashboard

* Overview of revenue, gross profit, units sold, and inventory.
* Key business performance indicators.
* Sales trends and category-level performance.
* Executive-level business insights.

### 📈 2. Sales Analytics

* Year-over-year revenue comparison.
* Daily, monthly, and seasonal sales analysis.
* Weekend versus weekday performance.
* Promotional versus non-promotional sales analysis.

### 🛍️ 3. Product & Category Analysis

* Product-level revenue and profitability analysis.
* Category-wise sales comparisons.
* Identification of top-performing products.
* Analysis of low-performing products.

### 📦 4. Inventory Intelligence

* Inventory valuation and stock-level analysis.
* Inventory turnover and days-on-hand calculations.
* Identification of slow-moving inventory.
* Overstock detection and excess inventory valuation.

### ⚠️ 5. Stockout Risk Detection

* Identification of products at risk of running out of stock.
* Comparison of current inventory with reorder points.
* Evaluation of stockout timelines against supplier lead times.
* Classification of products into CRITICAL, WARNING, and SAFE categories.

### 🔮 6. Demand Forecasting

* Revenue forecasting using time-series modeling.
* Actual versus forecast revenue visualization.
* 30-day demand outlook.
* Forecast confidence intervals.
* Category-level forecast analysis.

### 👥 7. Customer Analytics

* Customer segmentation into High Value, Regular, and Occasional groups.
* Customer revenue contribution analysis.
* Purchase frequency analysis.
* Customer behavior insights.

### 💡 8. Executive Recommendations

* Prioritized inventory recommendations.
* Identification of critical stockout risks.
* Overstock reduction opportunities.
* Revenue growth and profitability insights.
* Impact-versus-difficulty opportunity analysis.

---

## 🛠️ Technology Stack

| Technology                   | Purpose                                          |
| ---------------------------- | ------------------------------------------------ |
| Python                       | Data cleaning, preprocessing, and analysis       |
| Pandas                       | Data manipulation and transformation             |
| NumPy                        | Numerical computations                           |
| Scikit-learn / Statsmodels   | Demand forecasting and statistical modeling      |
| SQL                          | Data extraction, joining, and querying           |
| Power BI                     | Interactive dashboards and business intelligence |
| DAX                          | KPI calculations and analytical measures         |
| Power Query                  | Data transformation and preparation              |
| Excel                        | Data inspection and preparation                  |
| Git & GitHub                 | Version control and project documentation        |
| Streamlit / Power BI Service | Deployment options                               |

---

## 🏗️ System Architecture

The project follows a structured data analytics workflow, transforming raw business data into actionable business intelligence.

```text
       RAW BUSINESS DATA
  ┌─────────────────────────┐
  │ Sales                   │
  │ Products                │
  │ Inventory               │
  │ Customers               │
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │ Data Cleaning &         │
  │ Feature Engineering     │
  │ Python, Pandas, SQL      │
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │ Analytics & Modeling    │
  │ Demand Forecasting      │
  │ Stock Risk Analysis     │
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │ Power BI Data Model     │
  │ Relationships, DAX      │
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │ 12-Page Interactive     │
  │ Power BI Dashboard      │
  └────────────┬────────────┘
               │
               ▼
  ┌─────────────────────────┐
  │ Business Insights &     │
  │ Recommendations         │
  └─────────────────────────┘
```

---

## 📂 Dashboard Pages

The Power BI report contains 12 interactive dashboard pages.

| No. | Dashboard                    | Description                                    |
| --- | ---------------------------- | ---------------------------------------------- |
| 1   | Executive Dashboard          | Overall business performance and KPIs          |
| 2   | Sales Analytics              | Revenue trends and sales performance           |
| 3   | Product Performance          | Product-level revenue and profitability        |
| 4   | Category Performance         | Category-wise sales and profit analysis        |
| 5   | Inventory Dashboard          | Stock levels, valuation, and turnover          |
| 6   | Stockout Risk                | Critical inventory and replenishment risks     |
| 7   | Overstock Dashboard          | Excess stock and slow-moving inventory         |
| 8   | Promotion Dashboard          | Promotional sales performance                  |
| 9   | Seasonality Dashboard        | Seasonal and monthly demand patterns           |
| 10  | Forecast Dashboard           | Revenue forecasting and forecast intervals     |
| 11  | Customer & Business Insights | Customer segmentation and purchasing behavior  |
| 12  | Executive Recommendations    | Prioritized business actions and opportunities |

---

## 📊 Dataset Overview

The project analyzes daily retail transactions from **January 1, 2024, to December 31, 2025**.

| Metric              |               Value |
| ------------------- | ------------------: |
| Total Revenue       |        3.10 Billion |
| Gross Profit        |        1.22 Billion |
| Gross Profit Margin |               39.4% |
| Units Sold          |             511,810 |
| Number of Products  |                  50 |
| Product Categories  |                   5 |
| Customers           | Approximately 2,000 |
| Analysis Period     |           2024–2025 |
| Dashboard Pages     |                  12 |

### Product Categories

* Home Decor
* Furniture
* Storage
* Kitchen
* Lighting

---

## 🔍 Key Business Insights

The analysis revealed several important patterns in retail sales and inventory.

### 1. Revenue Performance

* Total revenue reached approximately 3.10 billion over the analysis period.
* Revenue remained nearly flat between 2024 and 2025.
* Home Decor contributed the largest share of total revenue.

### 2. Inventory Risks

* 727 products were classified as CRITICAL for stockout risk.
* 93 products were classified as WARNING.
* 3,980 products were classified as SAFE.

### 3. Overstock Analysis

* Approximately 2.37 billion in excess inventory value was identified.
* 36 products were classified as overstocked.
* 167 products were identified as slow-moving.
* Estimated annual holding costs for excess inventory were 41.46 million.

### 4. Seasonality

* March was identified as a strong sales month.
* Sales patterns varied across seasons.
* Weekend sales contributed significantly to overall revenue.

### 5. Customer Insights

* Customers were segmented into High Value, Regular, and Occasional groups.
* Regular customers contributed approximately 1.36 billion in revenue.
* High Value customers generated the highest revenue per customer.

---

## 💡 Business Recommendations

Based on the analysis, the platform provides the following recommendations:

1. **Reorder critical products:** Prioritize products at immediate risk of stockouts.
2. **Reduce excess inventory:** Consider targeted discounts and clearance strategies.
3. **Review low-performing products:** Evaluate products with consistently low revenue.
4. **Optimize reorder levels:** Align inventory decisions with seasonal demand patterns.
5. **Focus on high-growth products:** Use sales and profitability insights to support purchasing decisions.

---

📈 Dashboard Methodology

The project contains 12 interactive Power BI dashboards. Each dashboard focuses on a different aspect of retail business performance and inventory intelligence.

1. Executive Dashboard

Objective: Provide a high-level overview of business performance and key performance indicators.

Methodology:

Consolidated sales, revenue, profit, and inventory metrics into a single executive view.
Calculated total revenue, gross profit, gross profit margin, and units sold.
Analyzed revenue trends over time to identify high-performing and low-performing periods.
Compared revenue contributions across product categories.
Used KPI cards and trend visualizations to summarize business performance.

Key KPIs:

Total Revenue
Gross Profit
Gross Profit Margin
Units Sold
Revenue by Category
Daily Revenue Trend

Business Outcome: Provides management with a consolidated view of business performance and highlights important sales trends.

2. Sales Analytics Dashboard

Objective: Analyze sales performance and identify patterns in revenue generation.

Methodology:

Aggregated sales transactions by year, month, and weekday.
Compared annual revenue to identify year-over-year changes.
Analyzed daily and monthly sales trends.
Compared promotional and non-promotional revenue.
Examined weekday and weekend sales performance.
Used comparative charts to identify periods with higher sales activity.

Key KPIs:

Total Sales Revenue
Year-over-Year Revenue Growth
Monthly Revenue
Weekend vs. Weekday Revenue
Promotional vs. Non-Promotional Sales

Business Outcome: Helps identify revenue trends, understand sales patterns, and evaluate the contribution of promotional activity.

3. Product Performance Dashboard

Objective: Evaluate individual product performance based on revenue, sales volume, and profitability.

Methodology:

Aggregated sales data at the product level.
Calculated revenue and gross margin for individual products.
Ranked products by revenue contribution.
Compared product-level profitability and sales performance.
Examined revenue concentration to identify high-performing products and the long tail of lower-performing products.
Used product comparisons to highlight differences in performance.

Key KPIs:

Product Revenue
Units Sold
Gross Profit
Gross Margin per Unit
Top-Performing Products
Product Revenue Contribution

Business Outcome: Helps identify products that contribute significantly to revenue and products that may require further performance review.

4. Category Performance Dashboard

Objective: Compare revenue and profitability across the five product categories.

Methodology:

Grouped products into their respective categories.
Aggregated revenue and gross profit by category.
Calculated category-level profit percentages.
Compared revenue contributions across categories.
Analyzed monthly revenue trends for each category.
Used comparative visualizations to examine differences in category performance.

Key KPIs:

Revenue by Category
Gross Profit by Category
Profit Percentage
Monthly Category Revenue
Category Revenue Contribution

Business Outcome: Helps identify the categories contributing most to revenue and compare profitability across the product portfolio.

5. Inventory Dashboard

Objective: Monitor inventory levels, stock value, and inventory turnover.

Methodology:

Consolidated inventory data to analyze current stock levels.
Calculated total inventory value and units on hand.
Analyzed days on hand to understand how long inventory remains in stock.
Calculated inventory turnover to measure stock movement.
Compared inventory holding patterns across product categories.
Examined monthly inventory levels in relation to seasonal demand patterns.

Key KPIs:

Total Inventory Value
Units on Hand
Days on Hand
Inventory Turnover
Inventory Value by Category
Monthly Inventory Trends

Business Outcome: Helps identify slow-moving categories, monitor inventory investment, and understand whether stock levels align with demand patterns.

6. Stockout Risk Dashboard

Objective: Identify products that may run out of stock before new inventory arrives.

Methodology:

Compared current inventory against product reorder points.
Evaluated days until stockout for each SKU.
Compared estimated stockout timing with supplier lead times.
Classified products into three risk categories: CRITICAL, WARNING, and SAFE.
Analyzed stockout risk across products and categories.
Created SKU-level tables to support inventory review and replenishment planning.

Risk Classification:

Risk Level	Description
CRITICAL	Stock is expected to run out before replenishment can arrive.
WARNING	Inventory requires attention because of potential stock risk.
SAFE	No immediate stockout risk is identified by the classification.

Key KPIs:

Critical SKUs
Warning SKUs
Safe SKUs
Days Until Stockout
Reorder Point
Supplier Lead Time

Business Outcome: Helps identify products requiring urgent replenishment and supports more informed purchasing decisions.

7. Overstock Dashboard

Objective: Identify excess inventory and slow-moving products that increase inventory holding costs.

Methodology:

Analyzed inventory levels to identify overstocked products.
Calculated excess inventory value for affected products.
Identified slow-moving products and examined their inventory position.
Calculated the annual holding cost associated with excess inventory.
Estimated potential revenue recovery using a hypothetical 20% discount scenario.
Presented excess inventory metrics to support clearance and inventory reduction decisions.

Key KPIs:

Total Excess Inventory Value
Number of Overstocked Products
Slow-Moving Products
Annual Holding Cost
Potential Clearance Revenue

Business Outcome: Helps identify excess stock, understand its financial impact, and evaluate potential inventory clearance opportunities.

8. Promotion Dashboard

Objective: Analyze the relationship between promotional activity, sales volume, and revenue.

Methodology:

Separated promotional and non-promotional transactions.
Aggregated promotional revenue and units sold.
Compared promotional sales across product categories.
Analyzed product-level promotional performance.
Examined the relationship between promotional units and revenue.
Used comparative visualizations to understand the contribution of promotions to overall sales.

Key KPIs:

Promotional Revenue
Promotional Units Sold
Non-Promotional Revenue
Sales by Category
Product-Level Promotional Performance

Business Outcome: Helps businesses understand promotional sales patterns and identify products and categories with notable promotional revenue.

9. Seasonality Dashboard

Objective: Understand seasonal demand patterns and identify periods of high and low sales activity.

Methodology:

Added calendar-based features to the sales data.
Grouped transactions by season, month, and week.
Compared peak-season and off-season revenue.
Analyzed monthly sales fluctuations across the two-year period.
Examined weekly unit sales to identify periods of increased or reduced demand.
Compared seasonal performance between years.

Key KPIs:

Peak-Season Revenue
Off-Season Revenue
Seasonal Variation
Monthly Revenue
Weekly Units Sold
Revenue by Season

Business Outcome: Helps identify seasonal sales patterns and supports inventory planning around periods of higher or lower demand.

10. Demand Forecast Dashboard

Objective: Forecast future revenue and provide insights to support demand planning.

Methodology:

Aggregated historical sales revenue at the daily level.
Prepared historical data for time-series forecasting.
Trained a forecasting model using historical revenue data.
Held out a portion of historical data for validation.
Evaluated forecast accuracy using Mean Absolute Percentage Error (MAPE).
Generated future revenue forecasts with 95% prediction intervals.
Visualized actual revenue, forecast revenue, and upper and lower forecast bounds.
Presented a 30-day outlook and forecast revenue by category.

Key KPIs:

Actual Revenue
Forecast Revenue
30-Day Revenue Forecast
Upper and Lower Forecast Bounds
Forecast Accuracy (MAPE)
Forecast Revenue by Category

Business Outcome: Provides a forward-looking view of expected revenue to support purchasing, inventory, and business planning.

Note: The specific forecasting model name and validated MAPE value should be added once confirmed.

11. Customer and Business Insights Dashboard

Objective: Understand customer segmentation, purchasing behavior, and revenue contribution.

Methodology:

Grouped customers into High Value, Regular, and Occasional segments.
Analyzed the number of customers in each segment.
Aggregated revenue by customer segment.
Calculated revenue contribution and revenue per customer.
Examined purchase frequency across customer segments.
Compared category preferences and revenue distribution across segments.

Key KPIs:

Total Customers
Customers by Segment
Revenue by Segment
Revenue per Customer
Purchase Frequency
Category-Level Customer Revenue

Business Outcome: Helps businesses understand customer value, purchasing frequency, and the contribution of different customer segments to total revenue.

12. Executive Recommendation Dashboard

Objective: Bring important business metrics and analytical findings together to support management decisions.

Methodology:

Consolidated growth, profitability, inventory turnover, and stockout risk metrics.
Combined stockout risk counts with category-level analysis.
Developed a risk heat map to highlight inventory risk across categories.
Created an opportunity matrix comparing potential revenue impact with implementation difficulty.
Combined inventory, sales, and profitability insights into a prioritized action list.
Presented key recommendations in an executive-friendly format.

Key KPIs:

Revenue Growth
Gross Profit Margin
Inventory Turnover
Stockout Risk
Category-Level Risk
Opportunity Impact
Recommended Actions

Business Outcome: Converts analytical findings into a concise set of business actions, helping management focus on replenishment, excess stock, product performance, and inventory optimization.

## 📌 Challenges Faced

During development, the following challenges were addressed:

* Joining inventory records with the product master to ensure accurate category mapping.
* Aligning forecast values with actual daily revenue for meaningful comparisons.
* Writing DAX measures for ratios and KPIs that respond correctly to dashboard filters.
* Designing 12 dashboard pages while maintaining readability and consistency.

---

## 🔮 Future Scope

Potential future enhancements include:

* SKU-level demand forecasting.
* Automated reorder quantity recommendations.
* Scheduled data refresh.
* Automated alerts for critical stockout risks.
* Price and promotion optimization.
* Integration with real-time inventory systems.

---

## 📸 Dashboard Preview

Add screenshots of your Power BI dashboards here to showcase the project.

For example:

```markdown
![Executive Dashboard](screenshots/executive-dashboard.png)
![Sales Dashboard](screenshots/sales-dashboard.png)
![Inventory Dashboard](screenshots/inventory-dashboard.png)
```

Create a `screenshots` folder in your repository and upload the corresponding images.

---

## 🌐 Project Links

| Resource          | Link                                                 |
| ----------------- | ---------------------------------------------------- |
| GitHub Repository | [Project FORESIGHT](https://github.com/rinkle-YADAV) |
| Live Deployment   | Add your deployment URL                              |
| Demo Video        | Add your demo video link                             |
| Feedback Video    | Add your feedback video link                         |
| Project Report    | Add your report link                                 |

---

## 👩‍💻 Author

**Rinkle **
Data Analytics Intern

**Mentor:** Chandan Mishra

---

## 🏁 Conclusion

Project FORESIGHT demonstrates how data analytics, machine learning, and business intelligence can work together to improve retail demand planning and inventory management.

By combining demand forecasting, stockout risk detection, overstock analysis, and interactive dashboards, the platform helps transform complex retail data into practical business insights.

The project provides a foundation for more automated and data-driven inventory planning.

---

⭐ **If you find this project useful, consider giving the repository a star!**

