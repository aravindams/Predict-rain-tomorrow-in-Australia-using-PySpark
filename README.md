# Predict rain tomorrow in Australia using PySpark

PySpark application to predict rain tomorrow in Australia

## Summary

Predicting rain or weather is a common problem in machine learning. Different machine learning algorithms can be used to model and predict rainfall. A complete analysis to predict whether there will be rain tomorrow or not. The main of the application is predict the possibility of rainfall in Australia using **PySpark**, **EDA**, **Binary Classification Algorithms**.

## Data

The data given is weather data in .CSV format which is recorded on daily basis.

## Implementation

![alt text](https://github.com/aravindams/Predict-rain-tomorrow-in-Australia-using-PySpark/blob/main/image15.png)

**A. Creating Spark Session and Loading the Data**

SparkContext and SparkSession: We will use and import SparkContext from pyspark, which is the main entry point for Spark Core functionality. The SparkSession object provides methods used to create DataFrames from various input sources. A DataFrame is equivalent to a relational table in Spark SQL, and can be created using various functions in SparkSession. Once created, it can be manipulated using the various domain-specific-language (DSL) functions defined in: DataFrame, Column.

**B. Data Cleaning and Processing** 

Data cleaning and processing is an important aspect for any machine learning task. We have to carefully look into the data and based on the types, quality of the data, we have
to plan our cleaning procedures.

**C. Apply Machine Learning Algorithms**

Apply machine learning classification algorithms on the dataset and compare their accuracy: Using **DecisionTreeClassifier()**, **RandomForestClassifier()**, and **LogisticRegression()**, **GBTClassifier()** methods in spark to calculate the probability of the rain fall tomorrow based on the other related data points (e.g., temperature, wind, humidity). Finally, plotting the graph (e.g. bar chart) to demonstrate the comparison of their accuracy.

Calculate the **confusion matrix** and find the precision, recall, and F1 score of each classification algorithm: Finding the accuracy of the model does not always represent the quality of the model for a given dataset. Number of false positive and false negative identification also plays an important role when we decide about any particular classification model. The way we can calculate is called **confusion matrix**. confusionMatrix() method to calculate the confusion matrix. Finally, suggested how we can improve the accuracy of the prediction.
