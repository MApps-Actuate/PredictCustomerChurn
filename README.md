- In this magellan notebook, you will use Apache Spark and the Spark machine learning library to build a Customer Churn Prediction model.
- Customer Churn refers to when a customer ceases to complete target actions (e.g. add to cart, leave a comment, etc.) within a given period of time OR when a customer ceases his or her relationship with a company. 

In this notebook, you will learn how to:

1. Load data stored in Magellan Data Lake / Hadoop Distributed File System (HDFS)
2. Conduct data exploration
3. Clean and prepare data for model building
4. Create a machine learning pipeline using Apache Spark
5. Train, test and evaluate a model
6. Store a machine learning pipeline in the Magellan Data Lake Hadoop Repository
7. Explore and visualize the prediction results
8. Publish & deploy a machine learning pipeline to Big Data Analytics - so that operational users can access the model and make predictions

Steps :

1.	Import the following csv datasets:
- BDA spark – historical_churn_data
- BDA spark – customers_2019_Q1 (new data used for making predictions)
2.	Import “Churn prediction Using Apache Spark + Magellan” notebook and execute all cells 
3.	Publish model to BDA by following steps listed at end of notebook
4. Apply ML model on customers_2019_Q1 and save predictions as “customers_2019_Q1 _predictions” 
