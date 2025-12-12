# BigDataAnalysis_project

# BigDataAnalysis_project

In this project we demonstrate the capabilities of Spark for large-scale data processing, analysis, and machine learning.
We used three real-world datasets:

1. Wine Quality Dataset (Red & White Wines)
 - ~6,500 wine samples
 - Chemical properties (e.g. acidity, alcohol, pH)
 - Target: wine quality score (0–10)
 - Suitable for regression and classification tasks
   
2. Heart Failure Dataset
 - 918 patient records
 - Medical and demographic features
 - Target: presence of heart disease (0 = No, 1 = Yes)
 - Used for binary classification and health risk analysis
   
3. Airline Flight Delay & Cancellation Dataset (Aug 2019 – Aug 2023)
 - ~25–35 million flight records
 - One row = one domestic flight segment
 - Scheduled vs actual times, delays, cancellations, airlines, airports
 - Designed for big data analysis and time-series modeling

We explore how Spark can efficiently handle diverse analytical workloads, from raw data ingestion to predictive modeling and visualization. The goal of the project is to showcase a complete Big Data pipeline that integrates several components of the Spark ecosystem:
 - RDDs for low-level data manipulation and transformations
 - DataFrames & SparkSQL for structured analytics and SQL-based querying
 - Pipelines & Data Engineering for feature preprocessing and model automation
 - Machine Learning (Spark MLlib) for classification and regression tasks
 - GraphFrames for graph-based data relationships and network insights
 - MongoDB integration for real-time and persistence extensions

By combining multiple datasets — such as chemical properties of wines, product reviews, and sensor or demographic data — the project highlights Spark’s flexibility across different data domains.
The resulting pipeline includes data cleaning, feature engineering, visualization, and machine learning models (Decision Tree, Random Forest, Logistic Regression, SVM and Neural Networks), along with interpretability analysis and cross-dataset insights.
