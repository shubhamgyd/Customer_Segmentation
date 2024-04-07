# Project Objectives ✅
- **Identifying High-Value Customers:** To segment the customers based on their
  - Lifetime value,
  - Purchase frequency,
  - Average order value.

# Data Collection ✅
- Dataset: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis?select=marketing_campaign.csv)

# Data Preprocessing ✅
- To prepare the data for analysis:
  - Handling missing values
  - Standardizing or normalizing numerical features
  - Encoding categorical variables
  - Removing outliers

# Feature Selection/Engineering ✅
- **Total Amount Spent on Purchases:** Derived from the sum of spending on products
  - MntWines
  - MntFruits
  - MntMeatProducts
  - MntFistProducts
  - MntSweetProducts
  - MntGoldProds
- **Customer Lifetime Value (CLV):** Calculated based on historical transaction data
  - **Average Order Value (AOV):**
    - AOV = ∑(Total Amount Spent by the customer) / Total Number of Transactions by the customer
  - **Purchase Frequency (PF):**
    - PF = ∑(Total Number of Transactions) / Total Number of Unique Customers
  - **Customer Lifespan (CL):**
    - CL = Difference(current Purchase date, first Purchase date)
- **Formula for CLV:**
  - Simple CLV = AOV x PF x CL

# Future work

# Exploratory Data Analysis (EDA) ✅
- Conduct exploratory data analysis to gain insights into the characteristics and patterns within the data.
- Visualize the data using charts, graphs, and summary statistics to understand the distribution of variables and potential relationships between them.

# Clustering Algorithm Selection ✅
- Choose an appropriate clustering algorithm for segmenting the customers based on their similarities.
- For simplicity and efficiency, K-means is the best choice.

# Feature Scaling ✅

# Model Training ✅
- Apply the chosen clustering algorithm to the preprocessed data to create customer segments.
- Experiment with different values of parameters by increasing or decreasing the number of clusters for K-means and evaluate the quality of the resulting clusters using appropriate metrics.

# Interpretation and Profiling ✅
- Analyze the characteristics of each customer segment to understand their unique attributes and behavioral and transactional characteristics.

# Validation and Refinement ✅
- Validate the effectiveness of the segmentation by assessing its impact on marketing strategies or business goals.
- Refine the segmentation if necessary based on feedback or additional insights.

# Application ✅
- Apply the customer segments to inform marketing strategies, such as targeted messaging, personalized offers, product recommendations, or channel optimization.

# Monitoring and Iteration ✅
- Continuously monitor the performance of the segmentation model and iterate as needed to adapt to changing customer behaviors or business requirements.
