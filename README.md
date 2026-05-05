# Nigeria-Sales-Performance-Analysis.


Power BI analysis of 250k+ sales records focusing on regional drivers and customer retention in Nigeria. 


 ## Project Overview

Businesses often struggle to identify high-performing regions, understand customer purchasing behavior, and track sales team effectiveness across large datasets.

This project analyzes over *250,000* sales records across Nigeria to uncover key revenue drivers, evaluate customer value, and provide data-driven insights that support strategic decision-making.


**Key Objective:** To identify revenue drivers, optimize regional performance, and improve customer retention using data-driven insights.

## 🛠️ Tools & Technologies Used

- **Power BI:** Used for data visualization, report layout, and creating the interactive multi-page dashboard.

- **Power Query (M):** Utilized for data cleaning, transforming text-based location data into recognizable geographic formats, and normalizing the 250K+ order records.

- **DAX (Data Analysis Expressions):** Developed complex measures including:
*Average Revenue per Customer, Sales Median
 and Total Order Count*

 - **Geospatial Mapping:** Successfully mapped sales data to specific Nigerian States and Cities, ensuring accurate visualization of the *“Most Orders”* in hubs like Lagos, Ibadan, and Kano.


- **Data Modeling:** Implemented a clean **Star Schema** to ensure fast filtering across the 250,000 orders without lagging the report performance.


- **Trend Analysis:** The *“Monthly trend of median sales”* chart helps stakeholders understand the stability of sales independent of high-value outliers.


 - **Microsoft Excel:** Used as the primary data source for the raw transactional records.


## 🚀 Key Features & Insights

The dashboard is divided into four main functional areas:
1. 	**Sales Overview**

- **Executive KPIs:**  Real-time tracking of Total Sales (186bn), Total Orders (250K), and Sales Median (594K).

- **Geospatial Analysis:**  Visualization of sales distribution across Nigerian states and cities, identifying Lagos and Ibadan among top-performing hubs.

- **Trend Analysis:** Monthly monitoring of median sales to identify seasonal fluctuations.




![Sales_Overview](/Sales_Overview.png)




2.	**Customer Insights**

- **Top Tier Identification:** Analysis of the top 20 customers by total sales and order frequency.

- **Customer Retention:** Tracking the sales trends of top customers (e.g., Mark Ekwueme, Simon Balogun) over a 12-month period.

- **Regional Reach:**  Mapping states with the highest customer density.


![Customer_Insight](/Customer_Insight.png)


3.	**Product Performance**
- **Category Breakdown:** Balanced revenue distribution across Home Appliances, Electronics, Clothing, and Books, each contributing approximately 25%.

- **Inventory Insights:** Comparison of *“Top Products Sold”* vs. *“Total Quality of Products”* to identify high-volume items like Headphones and Microwaves.

- **Pricing Strategy:** Analysis of Average Sales per Product to determine premium vs. Volume-driven categories.



![Product_Performance](/Product_Performance.png)


4.	**Sales Rep Performance**

- **Individual Metrics:** Tracking total revenue and order counts for the sales team (Aisha Bello, Chinedu Okafor, Fatima Ahmed, and Musa Ibrahim).

- **Regional Dominance:** Identifying which sales representatives are most effective in specific Nigerian territories.


![Sales_Performance](/Sales_Performance.png)





## 💡 Final Conclusion & Recommendations

**Strategic Business Insights**

- High-Value Hubs: Analysis shows Lagos, Ibadan, and Port Harcourt are the highest-density regions. 

- Recommendation: Focus supply chain optimization and localized marketing in these areas to reduce delivery times and increase customer satisfaction.

- Revenue Stability: The business enjoys a healthy 25% split across all major categories (Electronics, Home Appliances, Clothing, Books). This diversification minimizes the risk of total revenue loss if one industry faces a downturn.

- Customer Retention: With 800 customers driving 186bn in sales, a small segment of the “Top 20” provides a huge percentage of the volume. A VIP loyalty program for these individuals is highly recommended to protect core revenue.



**Technical Summary**

- Scalability: The architecture was designed to handle 250,000+ orders while maintaining fast filter response times, proving the efficiency of the underlying Star Schema.

- Data Accuracy: By implementing strict data cleaning in Power Query, I ensured that geographical names and sales medians (594k) remained accurate across all 12 months, despite the large dataset.


