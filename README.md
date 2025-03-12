# Phase_3_Project


PHASE3_PROJECT: SyriaTel Customer Churn

**Problem Defination**

SyriaTel wants to predict customer churn using historical data. Additionally, they want to quantify the financial losses incurred by long-term customers who leave the service.

**Business Understanding**

SyriaTel, a TelecommunicationsCompany is concerned about customer churn the phenomenon where customers stop using their services. Some long-term customers may generate lower revenue while still incurring service costs, potentially leading to revenue losses. Understanding the characteristics of customers who are likely to churn will help the company take preventive measures.

**Data Preprocessing**

This section prepare the provided bigml data for analysis. We intend to do the following:

**Dataset Overview**

Load and explore the dataset to understand its structure, including available tables, columns, data types, and missing values.

Identify relevant data for analysis and determine which columns to focus on.

**Handling Missing Values**

Use domain knowledge and imputation techniques to manage missing values.

**Data Cleaning**

* Standardize categorical values.

* Derive useful date-related data.

* Remove duplicates and inconsistencies.

**Python Libraries Initialization**

First, we initialize common libraries we project to utilize in this exercise:

* pandas to create and manipulate dataframes

* seaborn and matplotlib to facilitate any requisite visualizations within the notebook

* numpy for mathematical calculations

* scikit-learn to provide tools for machine learning models, feature scaling, train-test-split and evaluation metrics.

**Data Understanding**

Exploratory Data Analysis

Used Notebook to explore the data and established the following insights:

 **1.churn distribution**

The majority of the customers do not curn indicating an imbalanced dataset. 
![churn d](https://github.com/user-attachments/assets/2bbe779c-1ca9-4da8-b215-c31caa6e1e67)

**2.Account length distribution for churned and non churned customers**

Both churn and non churned customers exist across various account lengths which shows that longer account lenngths result in churn. account length distribution
![account length distribution](https://github.com/user-attachments/assets/7ba7b7ba-9e40-41f4-868e-95a66117c531)

**3.correlation heatmap**

churn is highly correlated with customer service calls which indicates that Customers who makes more service calls are more likely to churn.
![heatmap](https://github.com/user-attachments/assets/53c4f10b-58e9-4e4c-9073-40d6bf9d6c5f)

h

**Model Performance & Evaluation**

We evaluated multiple models for churn prediction. Key findings include:

* All models achieved a recall of 74%, meaning they successfully detected most of the customers who actually churned.

* The Random Forest model performed the best with 94% accuracy and 96% precision.

**Recommendation**

 **Improve Customer Support**
 
Identify common customer complaints from high-frequency callers and address their concerns promptly.

**Enhance Customer Engagement**

Offer proactive support to customers making frequent service calls to improve satisfaction and retention.

**Handle Class Imbalance**

Use techniques like class weighting to improve model accuracy, as churned customers are fewer.

**Increase Model Recall**

If the company aims to capture more churners, recall should be improved to 80-85% or even 90%.

**Conclusion**

* Frequent customer service calls are a strong indicator of churn, highlighting customer dissatisfaction.

* The Random Forest model was the best-performing model with 94% accuracy.

* SyriaTel should improve customer support and engagement to reduce churn rates and enhance customer retention.
