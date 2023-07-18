# RFM-Analysis

This project demonstrates an RFM (Recency, Frequency, Monetary) analysis using Pandas, a popular Python library for data manipulation and analysis. RFM analysis is a valuable customer segmentation technique that helps businesses understand and categorize their customers based on their transactional behavior.

### Project Overview
The main objective of this project is to analyze customer transaction data and derive meaningful insights using the RFM model. RFM is a simple yet effective approach to customer segmentation, which helps identify different customer groups based on their recent purchase behavior, transaction frequency, and monetary value.

### RFM Calculation
To calculate the RFM scores, the following steps were performed:

• Recency (R): The number of days since the customer's most recent purchase. This was calculated by subtracting the maximum date in the dataset from each customer's PurchaseDate.

• Frequency (F): The total number of purchases made by each customer.

• Monetary Value (M): The total monetary value spent by each customer.

### Customer Segmentation
Based on the RFM scores, the customers were segmented into five distinct groups:
1. Champions: Customers with a combined RFM score of 9 or higher. These are highly valuable customers who have made recent purchases frequently with high monetary value.
2. Potential Loyalists: Customers with a combined RFM score of 6 to 8. They show potential for becoming loyal customers due to their moderate recency, frequency, and monetary value.
3. At Risk Customers: Customers with a combined RFM score of 5. These customers are at risk of churn as they show declining recency and need targeted retention efforts.
4. Can't Lose: Customers with a combined RFM score of 4. They are valuable customers but have low recency, and special attention is required to prevent them from becoming inactive.
5. Lost: Customers with a combined RFM score of less than 4. These are inactive or lost customers who need re-engagement strategies to win them back.

### Dependencies
pandas
plotly.express
plotly.io
datetime
plotly.graph_objects
numpy


link to article - https://tinyurl.com/poornima-rfm-analysis
