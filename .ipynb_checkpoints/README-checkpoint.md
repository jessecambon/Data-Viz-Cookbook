# The Data Science Codex

A collection of code and resources to serve as a starting point for data science projects. 

<span>
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Chart_Collection.md#lollipop"><img src="https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Chart_Collection_files/figure-markdown_github/lollipop-1.png" height="200px"/></a>
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Chart_Collection.md#bubbleplot"><img src="https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Chart_Collection_files/figure-markdown_github/bubbleplot-1.png" height="200px"/></a>
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Geospatial_Analysis.md"><img src="https://github.com/jessecambon/Data-Science-Codex/blob/master/source/Geospatial_Analysis_files/figure-markdown_github/unnamed-chunk-2-1.png" height="200px"/></a> 
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Chart_Collection.md#ridgeplot"><img src="https://raw.githubusercontent.com/jessecambon/Data-Science-Codex/master/source/Chart_Collection_files/figure-markdown_github/ridge-1.png" height="200px"/></a> 
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Titanic.md#logistic-regression-model"><img src="https://github.com/jessecambon/Data-Science-Codex/blob/master/source/Titanic_files/figure-markdown_github/logistic-regression-2.png" height="200px"/></a> 
<a href = "https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Titanic.md#logistic-regression-model"><img src="https://github.com/jessecambon/Data-Science-Cookbook/blob/master/source/Titanic_files/figure-markdown_github/logistic-regression-1.png" height="200px"/></a> 
</span>


The purpose of this repository is to provide code and resources that can be quickly adapted and used for data science projects. An emphasis is placed on having clear understandable code that can be easily replicated. I make use of inbuilt datasets in R so that there is no need to download external datasets.


## General 
* [Resources](Resources.md) - Websites and references that I find helpful for data science projects.
* [Creating Formatted Spreadsheets](source/Create_Formatted_Spreadsheet.md) - How to create a custom formatted spreadsheet report with the openxlsx R package.
* [Using Python and R Together](source/R-Python-Hybrid.ipynb) - How to use python and R code together in the same Jupyter notebook with the rpy2 python package.
* [R Quotation](source/R_Quotation.md) - If you want to do certain things such as pass variable names as arguments to a function in R, you have to use quotation methods like quo() and enquo(). This notebook demonstrates how to do this.
* [Pandas Counting](source/Pandas_TidyCount.ipynb) - A function for counting values or combinations of values in a pandas dataframe. This function does not exclude missing values.

## Data Visualization
* [Visualization Cookbook](source/Chart_Collection.md) - A wide variety of data visualizations demonstrated.
* [Geospatial Data Analysis](source/Geospatial_Analysis.md) - A work-in-progress collection of maps. 

## Modeling and Machine Learning 
* [Modeling Fundamentals](source/Titanic.md) - A primer on logistic and linear regression modeling with the classic Titanic dataset.
* [Modeling Workflows](source/Modeling_Workflow.md) - Streamlined Tidyverse modeling workflows with the gapminder dataset.
* [Clustering](source/Clustering.md) - Using the k-means alogrithm to cluster data.
* [Machine Learning with Caret](source/Caret.md) - Using the Caret library to do machine learning.
* [Predicting Fuel Economy](source/Vehicles.md) - Predicting the fuel economy of cars.
* [Ordinal Regression](source/Ordinal_Regression.md) - Experimenting with ordinal (ranked categorical outcome) regression
* [Presenting Regression Models](source/Regression_Model_Tidying.md) - Code for cleaning the outputs of regression models

## NLP 
* [Document Embeddings](source/state_of_union_embeddings.ipynb) - Using document embeddings to find similar state of the union addresses.
* [Hello NLP](source/Hello_NLP.ipynb) - Testing out some NLP techniques on Wall Street Journal sample data
* [State of the Union Analysis](source/state_of_union_v2.ipynb) - An exploration of state of the union addresses with NLP
* [LSTM Demo](source/LSTM-Demo.ipynb) - An LSTM network for predicting if a company review from glassdoor is positive