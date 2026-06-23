# Sharktank_analysis Project
pick dataset from kaggle and cleaning ,preprocessing,EDA proccess apply,behaviour analysis,statistical analysis perform and ready dataset for machine learning model as a data analyst

Project Overview:
This project focuses on analyzing Shark Tank USA data to understand the factors that influence investment decisions and deal outcomes.
The dataset was cleaned, transformed, and analyzed using Python to uncover business insights, identify trends, and prepare the data for future dashboarding and machine learning applications.
The primary objective was to convert raw data into an analytics-ready dataset while demonstrating the complete Data Analyst workflow.

Business Problem
Entrepreneurs enter Shark Tank seeking investments from experienced investors.
This project aims to answer questions such as:

--Which industries receive the most deals?
--Do founder teams perform better than solo founders?
--Does company valuation impact deal success?
--Are smaller funding requests more likely to receive investments?
--What characteristics influence investment outcomes?

Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Project Workflow

1. Data Understanding
Performed an initial assessment of the dataset:
--Dataset shape
--Column definitions
--Data types
--Business understanding of features

Key methods:
df.head()
df.info()
df.describe()

2. Data Cleaning
Performed data quality checks including:
--Missing Values
--Identified missing records
--Treated missing values using business logic
--Duplicate Records
--Detected and removed duplicate observations
--Data Type Conversion
Converted columns into appropriate formats:
--Numeric columns
--Datetime columns
--Categorical columns
Examples:
--Original Air Date → Datetime
--Financial fields → Numeric

4. Feature Categorization
Features were categorized into:
-Numerical Features
--Original Ask Amount
--Investment Amount
--Valuation
--Equity Percentage
-Categorical Features
--Industry
--Pitchers Gender
--Deal Type
-Binary Features
--Got Deal
--Multiple Entrepreneurs
---Shark Presence Indicators
-Date Features
--Original Air Date

4. Exploratory Data Analysis (EDA)
Univariate Analysis
--Analyzed individual variables using:
--Histograms
--Countplots
--Summary statistics
-Objectives:
--Understand distributions
--Detect anomalies
--Identify skewness

6. Outlier Detection
Detected outliers using:
--Boxplots
--sns.boxplot()

IQR Method
Calculated:
--Q1
--Q3
--IQR
--Upper Bound
--Lower Bound

Analyzed extreme values before deciding whether removal was appropriate.

6. Bivariate Analysis
Studied relationships between variables and deal outcomes.
Key analyses included:
--Industry vs Got Deal
--Ask Amount vs Got Deal
--Valuation vs Got Deal
--Age Group vs Got Deal
--Multiple Entrepreneurs vs Got Deal
--Gender vs Got Deal

Methods:
--Crosstab Analysis
--Percentage Analysis
--Boxplots
--Heatmaps

7. Feature Engineering
Created business-focused features to improve analytical value.
--Company Valuation
--Valuation =
--Original Ask Amount /
(Original Offered Equity / 100)
--Founder Team Flag

Created a feature indicating:
--Solo Founder
--Multiple Founders
--Date Features

Extracted:
--Year
--Quarter
--Additional Derived Features
--Equity Ratio
--Deal Success Indicators
--Business Performance Metrics

8. Data Validation
Performed additional validation checks:
--Missing value verification
--Infinite value detection
--Data type consistency checks

Examples:

----X.isnull().sum()
---np.isinf(X).sum()

This ensured the dataset was suitable for future predictive modeling.

Key Insights::
Industry Impact
Certain industries consistently achieved higher deal success rates.
Founder Teams
Teams demonstrated a higher probability of receiving investment compared to solo founders.
Valuation Effect
Higher valuation expectations often reduced the likelihood of securing a deal.
Funding Requests
Companies requesting smaller investments generally showed stronger deal success rates.
Investor Participation
The presence of specific sharks appeared to influence deal outcomes and negotiation patterns.


Project Outcome::
At the completion of this project:

Raw data was transformed into an analytics-ready dataset.
Data quality issues were resolved.
Business-focused features were engineered.
Actionable insights were generated.
The dataset was prepared for dashboard development and machine learning applications.
Skills Demonstrated
Data Cleaning
Missing Value Treatment
Duplicate Handling
Data Type Conversion
Exploratory Data Analysis
Univariate Analysis
Bivariate Analysis
Outlier Detection
Feature Engineering
Business Metric Creation
Date Feature Extraction
Derived Variable Development
Data Visualization
Countplots
Boxplots
Heatmaps
Comparative Analysis
Analytical Thinking
Business Problem Solving
Insight Generation
Decision-Oriented Analysis

Next Phase
-The cleaned dataset will be used in the next stage of the project:
-Power BI Dashboard Development
-Planned dashboard componentsExecutive Summary
-Deal Success Analysis
-Industry Performance Dashboard


-Shark Performance Dashboard
-Investment Trends Analysis
![App Screenshot](https://github.com/user-attachments/assets/984e7877-b335-4186-8a43-46ae95ccf54b)

----Conclusion-------
This project demonstrates the complete Data Analyst workflow from raw data to actionable insights. Through systematic data cleaning, exploratory analysis, and feature engineering, the dataset was transformed into a reliable foundation for business intelligence reporting and predictive analytics.
