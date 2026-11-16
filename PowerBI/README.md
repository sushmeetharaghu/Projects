# ShopNest Store Sales Analysis | Power BI Dashboard

An interactive Power BI dashboard that explores ShopNest's e-commerce sales, delivery performance, payment preferences, regional performance, and customer satisfaction. The report combines data from nine tables into a single-page dashboard, with Month/Year and Customer State slicers for interactive analysis.

## Dashboard Preview

![ShopNest Power BI dashboard overview](images/dashboard_overview.png)

## Key Performance Indicators

![Key performance indicators](images/key_metrics.png)

| KPI | Value |
|---|---:|
| Total Revenue | 16.01M |
| Total Sales | 13.65M |
| Average Order Value | 160.99 |
| Average Review Score | 4.02 / 5 |
| Delayed Orders | 7.87% |
| Total Freight Value | 2.26M |

## Business Questions & Visual Insights

### 1. Top 10 Product Categories by Sales
Identifies the product categories generating the highest sales. Health & Beauty leads, followed by Watches & Gifts and Bed, Bath & Table.

![Top 10 product categories by sales](images/top_categories_sales.png)

### 2. Delayed Orders by Product Category
Compares the number of delayed orders across product categories. Bed, Bath & Table records the highest number of delayed orders in the report.

![Delayed orders by category](images/delayed_orders_by_category.png)

### 3. Monthly On-Time vs. Delayed Orders
Compares monthly delivery performance and includes a drill-through experience for more detailed order analysis.

![Monthly delivery performance](images/monthly_delivery_performance.png)

### 4. Payment Method Analysis
Shows the distribution of customer payment methods. Credit cards account for the largest share (73.92%), followed by Boleto (19.04%).

![Payment method distribution](images/payment_methods.png)

### 5. Product Category Ratings
Highlights the ten highest-rated and ten lowest-rated product categories based on average review score.

**Top 10 rated categories**

![Top 10 rated categories](images/top_rated_categories.png)

**Bottom 10 rated categories**

![Bottom 10 rated categories](images/lowest_rated_categories.png)

### 6. State-wise Sales Performance
Compares sales across customer states. São Paulo is the highest-selling state, followed by Rio de Janeiro and Minas Gerais.

![State-wise sales](images/state_wise_sales.png)

### 7. Quarterly Sales Trends
Explores quarterly sales patterns across the available years to understand changes in sales performance over time.

![Quarterly sales trends](images/quarterly_sales_trends.png)

### 8. Revenue Trends
Tracks revenue over time and highlights key monthly revenue milestones. Total revenue across the dataset is 16.01M.

![Revenue trends](images/revenue_trends.png)

## Skills Demonstrated

- Data cleaning and transformation
- Data modeling and table relationships
- DAX measures and KPI development
- Business and sales analysis
- Data visualization and dashboard design
- Interactive filtering and drill-through reporting

## Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query** – data cleaning and transformation
- **DAX** – calculated measures and KPIs

## Data Model

The report brings together nine source tables:

- Customers
- Geolocation
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Product Category Translation

## Key Takeaways

- Health & Beauty is the leading product category by sales.
- São Paulo contributes the highest state-wise sales.
- Credit card is the most frequently used payment method.
- The average customer review score is 4.02 out of 5.
- Delayed orders represent 7.87% of orders, according to the report's KPI.
- Revenue grows substantially through 2017 and remains at a comparatively high level through much of 2018 before the dataset ends.

## How to View the Project

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop** (if included in the repository).
3. Use the Month/Year and Customer State slicers to explore the dashboard.
4. Right-click a month in the monthly delivery visual to access the configured drill-through analysis.

---

*This project was created to demonstrate practical Power BI skills through an interactive e-commerce sales and operations analysis.*
