# Car Sales Analysis (EDA)

[![](https://raw.githubusercontent.com/anuraggupta4u/car-sales-analysis/main/images/EDA%20Image.jpg)](https://raw.githubusercontent.com/anuraggupta4u/car-sales-analysis/main/images/EDA%20Image.jpg)

## Contents

- Introduction
- Problem Statement
- Importing Libraries
- Data Acquisition & Description
- Data Pre-Profiling
- Data Pre-Processing
- Data Post-Profiling
- Exploratory Data Analysis
- Summarization 
 - Conclusion
 - Actionable Insights

## Problem Statement

The notebooks explores the basic use of Pandas and will cover the basic commands of Exploratory Data Analysis(EDA) which includes cleaning, munging, combining, reshaping, slicing, dicing, and transforming data for analysis purpose.

Exploratory Data Analysis

Understand the data by EDA and derive simple models with Pandas as baseline. EDA ia a critical and first step in analyzing the data and we do this for below reasons :
•Finding patterns in Data
•Determining relationships in Data
•Checking of assumptions
•Preliminary selection of appropriate models
•Detection of mistakes

## Data Acquisition & Description

The dataset comprises 9576 observations of 10 columns. Below is a table showing names of all the columns and their descriptions.

|Feature   | Description  |
| ------------ | ------------ |
| car  | Car brand name |
| model | Available car different Variants  |
|  year | Purchasing Year   |
| body  | Body type-Hatchback, Sedan, Crossover etc.  |
| mileage  | Car Mileage  |
| engV  | Engine Version  |
| engType  |Car Fuel Type - Petrol, Diesel, Gas etc.   |
| drive  | Wheel Drive Front, Rear  |
| registration  |  Check if the vechile is registered |
| price  | Price of Car in $  |

## Key Observations

- Car has high cardinality. 87 distinct values.
- Drive and engV have 511 and 434 missing values respectively.
- Mileage and Price have 348 and 267 Zeros respectively.
- Model has high cardinality. 888 distinct values.
- Dataset has 113 duplicate rows.

[Python Notebook Link](https://github.com/anuraggupta4u/car-sales-analysis/blob/main/Analysis%20on%20Car%20Sales.ipynb "Python Notebook Link")






