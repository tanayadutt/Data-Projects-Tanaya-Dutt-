# **STUDENT PERFORMANCE FACTORS ANALYSIS**

## Overview

This project focuses on cleaning, analyzing and visualizing data related to various factors that might affect a students 
at school. The primary goal is to ensure that the dataset is clean and ready for analysis. I also performed some basic Exploratory
Data Analysis to answer a few questions.

## About the Dataset
I picked this dataset from Kaggle, it is called the Student Performance Factors dataset. It contains a range of academic, social and personal factors that might influence a student's performance. I studied the relationship between these variables and student outcomes, particularly ```Exam_Score```.


## Key Steps
1. Data Loading:
   - Loaded the dataset using PANDAS library
2. Data Cleaning:
   - Addressed missing values
   - Duplicates were removed
   - Columns with incorrect data type were converted
3. EDA:
   - Basic summary stats displayed using ```df.describe()```
   -  Univariate Analysis:  ```value_counts()``` for categorical variables, histogram to analyze the distribution of the ```Exam_Score```
   - Multivariate Analysis: Bar charts to examine the distribution between ```Attendance``` and ```Exam_Score```
   - Scatter plot to visualize the relationship between ```Hours_Studied``` and ```Exam_Score```, ```Previous_Scores``` and ```Exam_Score``` and ```Sleep_Hours``` and ```Exam_Score```.
   - Correlation Matrix to show strongest predictors for the ```Exam_Score```


## Key Insights
1. The correlation matrix suggests a strong positive realtion between ```Exam_Score``` and ```Attendance```. This means that students who attent more classes tend to score higehr on their exams.
2. The scatter plot between ```Hours_Studied``` and ```Exam_Score``` suggests that studying more hours **generally** resulys in better examscores, although there is a significant variability among students who studied fewer hours.
