# Predict rain tomorrow in Australia using PySpark

PySpark application to predict rain tomorrow in Australia

## Summary

Predicting rain or weather is a common problem in machine learning. Different machine learning algorithms can be used to model and predict rainfall. A complete analysis to predict whether there will be rain tomorrow or not. The main of the application is predict the possibility of rainfall in Australia using **PySpark**, **EDA**, **Binary Classification Algorithms**.

## Data

The data given is weather data in .CSV format which is recorded on daily basis.

## Implementation

**Creating Spark Session and Loading the Data**

SparkContext and SparkSession: We will use and import SparkContext from pyspark, which is the main entry point for Spark Core functionality. The SparkSession object provides methods used to create DataFrames from various input sources. A DataFrame is equivalent to a relational table in Spark SQL, and can be created using various functions in SparkSession. Once created, it can be manipulated using the various domain-specific-language (DSL) functions defined in: DataFrame, Column.
