# Customer-Lifetime-Value-CLV-Prediction-and-Product-Recommendation
This project aims to predict Customer Lifetime Value (CLV) and provide product recommendations based on customer purchasing behavior. The project uses historical sales data from an online retail store to derive insights into customer segments and recommend products to improve marketing strategies.


Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation
numpy for numerical operations
matplotlib and seaborn for data visualization
sklearn for machine learning algorithms

Data Source: Excel file containing online retail sales data

Dataset
The dataset used in this project is Online_Retail_II.xlsx, specifically from the Year 2010-2011 sheet. The data contains information about customer purchases, including:
Customer ID
Product details (StockCode, Description)
Quantity purchased
Invoice date and other relevant details
Methodology

Data Preprocessing:
Loaded the dataset and removed rows with missing customer IDs.
Cleaned the data by filtering out negative quantities (returns).
Handled missing values for critical fields.

Feature Engineering:
Calculated the Monetary, Frequency, and Recency metrics for each customer.
Merged these features into a single RFM dataframe.

CLV Prediction:
Built a Linear Regression model to predict CLV based on RFM metrics.
Evaluated the model's performance using Mean Absolute Error (MAE).

Customer Segmentation:
Normalized the RFM data and applied K-Means clustering to segment customers into distinct groups.

Product Recommendation:
Created a collaborative filtering recommendation system based on customer purchase history using cosine similarity.


# Results
The project provides the following insights:
Predicted Customer Lifetime Value (CLV) for each customer.
Customer segments based on purchasing behavior.
Top product recommendations for a selected customer.

Visualizations:
Visualizations include scatter plots representing customer segments based on Recency and Frequency, which help in understanding customer behavior and identifying marketing strategies.




    
    
