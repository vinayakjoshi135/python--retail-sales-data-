# python--retail-sales-data-
**Retail Sales Analysis
Project Overview**

This project focuses on analyzing retail sales data and building machine learning models to predict monthly sales. The primary objective is to identify key factors influencing sales and recommend the best-performing model for reliable predictions.

** Dataset Description**

The dataset Retail_Sales_Data contains records for 1000 retail stores with the following attributes:

Monthly Sales (Target Variable)

Advertising Budget

Store Size (sqft)

Number of Employees

Customer Satisfaction Rating

Distance to Competitor

Average Product Price

Location Type: Urban / Suburban / Rural

Season: Winter / Spring / Summer / Fall

**Exploratory Data Analysis (EDA)**

Key findings from the analysis:

Most stores are located in suburban areas.

Higher advertising budget and larger store size generally lead to better sales.

Customer satisfaction strongly influences sales.

Sales fluctuate with seasons, with Fall showing higher sales frequency.

Correlation analysis showed strong positive relationships between:

Advertising Budget ↔ Monthly Sales

Store Size ↔ Monthly Sales

Customer Satisfaction ↔ Monthly Sales

**Data Preprocessing**

Converted categorical variables (Location Type, Season) into numerical format.

Split the dataset into:

Features (X): All variables except monthly sales

Target (y): Monthly sales

Performed an 80-20 train-test split.

**Model Building**

Two models were implemented:

Decision Tree Classifier

Easy to interpret, but prone to overfitting.

Random Forest Model

Ensemble approach with multiple decision trees.

Provided better accuracy and reliability compared to Decision Tree.

**Model Evaluation & Results**

Decision Tree:

Training Accuracy: High

Validation Accuracy: Moderate (overfitting observed)

Random Forest:

Training Accuracy: Higher than Decision Tree

Validation Accuracy: Higher than Decision Tree

Confusion Matrix showed fewer errors and more correct predictions

**Conclusion**: Random Forest outperforms Decision Tree and should be preferred for sales prediction tasks.

**Key Insights**

Advertising Budget is the strongest predictor of sales.

Store Size and Customer Satisfaction also play major roles.

Season and Location Type impact sales trends.

Random Forest is more robust and reliable for prediction.

**Conclusion**

This project provided hands-on experience in:

Data exploration and visualization

Preprocessing categorical and numerical features

Building and evaluating machine learning models

Extracting business insights from data

The learnings can be applied to real-world retail decision-making and strategy development.

**Contributors**

Vinayak Joshi 

Nidhi Lakhe 

Manik Tangade 




