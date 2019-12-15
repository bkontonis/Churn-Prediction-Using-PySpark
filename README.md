# Churn Prediction on Sparkify dataset Using PySpark
A binary classification problem using Spark and Spark's MLlib.
[Medium Post](https://medium.com/@kontonisbill/churn-prediction-on-sparkify-dataset-using-pyspark-d2ac315a237a)

## Project Description
In this project, we use the Sparkify dataset and try to predict the potential churners using Machine Learning. We use PySpark and Spark MLlib.
The process includes the following steps:
 1. Load and Clean the Data
 2. Exploratory Data Analysis
 3. Feature Engineering
 4. Machine Learning Models

## Dependencies
- Python 3.6.3
- numpy==1.12.1
- pandas==0.23.3
- pyspark==2.4.3
- seaborn==0.8.1
- matplotlib

## Files Explanation
- VK_Sparkify.ipynb
  - A notebook contains all the analysis codes.

## Analysis Results
- Best model: `LogisticRegression(msxIter=10)`
- Best f1-score: 0.80
- Top feature importances:
  - Roll Adverts per hour
  - Thumbs Down per hour
  - Sessions (negative coefficient)
