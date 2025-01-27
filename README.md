# Data-Science-Assignment-eCommerce-Transactions-Dataset
This repository contains the deliverables for the Data Science assignment, focusing on analyzing an eCommerce transactions dataset. The project includes tasks related to exploratory data analysis (EDA), lookalike modeling, and customer segmentation using clustering techniques.
File Descriptions
# Kongani_SaiManikantaYadav_EDA.ipynb:
Jupyter notebook containing the Python code for the Exploratory Data Analysis (EDA).
# Kongani_SaiManikantaYadav_EDA.pdf:
PDF report summarizing the EDA results and business insights derived from the dataset.
# Kongani_SaiManikantaYadav_Clustering.ipynb: 
Jupyter notebook containing the implementation of the customer segmentation using clustering techniques.
# Kongani_SaiManikantaYadav_Clustering.pdf: 
PDF report detailing the clustering analysis, evaluation metrics, and visualizations.
# Kongani_SaiManikantaYadav_Lookalike.ipynb:
Jupyter notebook containing the implementation of the Lookalike Model.
# Kongani_SaiManikantaYadav_Lookalike.csv: 
CSV file containing the similarity scores and top 3 lookalike recommendations for the first 20 customers.
# Overview
The project aims to derive actionable insights and build machine learning models using the following datasets:

# Customers.csv: 
Information about customers, including CustomerID, CustomerName, Region, and SignupDate.
# Products.csv:
Details of products, such as ProductID, ProductName, Category, and Price.
# Transactions.csv:
Transactional data including TransactionID, CustomerID, ProductID, TransactionDate, Quantity, and TotalValue.
Assignment Tasks
# Task 1: 
Exploratory Data Analysis (EDA) and Business Insights
Objective: Analyze the datasets to uncover key trends and patterns.
Deliverables:
EDA notebook with code.
PDF report with at least five business insights.
# Task 2: 
Lookalike Model
Objective: Build a model to recommend three similar customers for a given customer based on profile and transactional history.
Deliverables:
Jupyter notebook with the model implementation.
CSV file with the similarity scores and top 3 lookalike customers for CustomerID C0001 to C0020.
# Task 3:
Customer Segmentation / Clustering
Objective: Segment customers into clusters using their profile and transaction data.
Deliverables:
Clustering notebook with implementation.
PDF report summarizing the clustering results, DB Index, and visualizations.
Insights Derived
# From EDA:
# Regional Customer Distribution:
Key regions with high customer density and opportunities for marketing expansion.
# Best-Selling Product Categories:
Categories generating the most revenue and potential areas for improvement.
# High-Value Transactions Trends:
Seasonal trends indicating opportunities for targeted promotions.
# Customer Retention:
Insights into repeat purchase rates and strategies for boosting customer loyalty.
# Price Sensitivity:
Correlation between price ranges and transaction volumes.
# From Clustering:
The segmentation revealed distinct customer groups with varying behaviors.
Optimal number of clusters determined using metrics like the DB Index.
# From Lookalike Model:
Recommendations are generated using similarity scores to target customers with similar behaviors effectively.
# Tools and Libraries Used
# Programming Language: 
Python
# Libraries:
# Data Analysis: 
pandas, numpy
# Visualization: 
matplotlib, seaborn
# Machine Learning: 
scikit-learn
# Clustering and Evaluation:
KMeans, DB Index
