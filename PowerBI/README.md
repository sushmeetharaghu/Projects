# ShopNest Store Sales Analysis | Power BI Dashboard

An interactive Power BI dashboard that explores ShopNest's e-commerce sales, delivery performance, payment preferences, regional performance, and customer satisfaction. The report combines data from nine tables into a single-page dashboard, with Month/Year and Customer State slicers for interactive analysis.

## Dashboard Preview

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/046779b3-fdf9-4c50-9917-3a2044e46483" />


## Key Performance Indicators

<img width="700" height="76" alt="image" src="https://github.com/user-attachments/assets/eeb8e942-fa92-4d34-83b3-388186515171" />


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

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/59e338da-ab53-4345-84b3-5d3b2a9d2f09" />


### 2. Delayed Orders by Product Category
Compares the number of delayed orders across product categories. Bed, Bath & Table records the highest number of delayed orders in the report.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/ba35eae3-41d9-4115-ab7e-eb54d2d2a1f6" />


### 3. Monthly On-Time vs. Delayed Orders
Compares monthly delivery performance and includes a drill-through experience for more detailed order analysis.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/45819696-1846-42e8-a70a-323956d1e0b8" />


### 4. Payment Method Analysis
Shows the distribution of customer payment methods. Credit cards account for the largest share (73.92%), followed by Boleto (19.04%).

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/ee81d54a-f478-4c95-9069-9291e236fad5" />


### 5. Product Category Ratings
Highlights the ten highest-rated and ten lowest-rated product categories based on average review score.

**Top 10 rated categories**

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/af9408c7-cbf8-45ba-892a-9bfe71012c8d" />


**Bottom 10 rated categories**

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/0e43db24-b2bd-4e89-8945-572b7bde6420" />


### 6. State-wise Sales Performance
Compares sales across customer states. São Paulo is the highest-selling state, followed by Rio de Janeiro and Minas Gerais.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/ed75ed31-7226-4909-9597-5dc55d487904" />


### 7. Quarterly Sales Trends
Explores quarterly sales patterns across the available years to understand changes in sales performance over time.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/6e7819ad-1c7a-4b51-98b7-dff4740d9258" />


### 8. Revenue Trends
Tracks revenue over time and highlights key monthly revenue milestones. Total revenue across the dataset is 16.01M.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/c7379d82-946d-4137-b920-5779a93cce01" />


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
