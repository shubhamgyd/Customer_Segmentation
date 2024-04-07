1. Define Objectives ✅
➡️ Identifying High-Value Customers: To segement the customers based on their
    🎯 lifetime value,
    🎯 purchase frequency,
    🎯 average order value.

2. Data Collection ✅
➡️ https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis?select=marketing_campaign.csv

3. Data Preprocessing ✅
➡️ To preprocess the data to prepare it for analysis:
    🎯 Handling missing values
    🎯 standardizing or normalizing-numerical features
    🎯 encoding categorical variables
    🎯 removing outliers

4. Feature Selection/Engineering ✅
➡️ Total Amount Spent on Purchases: Derived from the sum of spending on products
    🎯 MntWines
    🎯 MntFruits
    🎯 MntMeatProducts
    🎯 MntFistProducts
    🎯 MntSweetProducts
    🎯 MntGoldProds
➡️ Customer Lifetime Value (CLV): Calculated based on historial transaction data
              
    🎯 Average Order Value (AOV):
          AOV = ∑(Total Amount Spent by the customer) / Total Number of Transactions by the customer
    
    🎯 Purchase Frequency (PF):
          PF = ∑(Total Number of Transactions) / Total Number of Unique Customers
    
    🎯 Customer Lifespan (CL):
          CL = Difference(current Purchase date, first Purchase date)

    🏁🏁🏁🏁🏁🏁🏁🏁🏁🏁🏁🏁
    Formula for CLV:
            🎯 Simple CLV = AOV x PF x CL

// Future work

5. Exploratory Data Analysis (EDA) ✅
➡️ To conduct exploratory data analysis to gain insights into the characteristics and patterns within 
    the data.
➡️ Visualize the data using charts, graphs, and summary statistics to understand the distribution of 
    variables and potential relationships between them.

6. Clustering Algorithm Selection ✅
➡️ Now, to choose an appropriate clustering alogrithm for segmenting the customers based on their 
   similarities.
➡️ But for simplicity and efficiency, K-means is the best choice.

7. Feature Scaling ✅

8. Model Training ✅
➡️ To apply the choosen clustering algorithm to the preprocessed data to create customer segments.
   Experiment with different values of parameters by increasing or decreasing the number of clusters
   for K-means and evaluate the quality of the resulting clusters using appropriate metrics.

9. Interpretation and Profiling ✅
➡️ To analyze the characteristics of each customer segment to understand their unique attributes and
   behavioral, and transactional characteristics.

10. Validation and Refinement ✅
➡️ To validate the effectiveness of the segmentation by assessing its impact on marketing strategies
   or business goals. Refine the segmentation in necessary based on feedback or additional insights.

11. Application ✅
➡️ Apply the customer segments to inform marketing strategies, such as targeted messaging, personalized
   offers, product recommendations, or channel optimization.

12 Monitoring and Iteration ✅
➡️ Continuously monitor the performance of the segmentation model and iterate as needed to adapt to
   changing customer behaviors or business requirements.