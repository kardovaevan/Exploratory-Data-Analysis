# Exploratory-Data-Analysis
EDA for E-Commerce Shipping Data by Kardova Evan Putra

## Introduction
In this repository, I will perform Exploratory Data Analysis (EDA) on E-Commerce Shipping Data from an international e-commerce company. 

## Data Explanation
source : https://www.kaggle.com/prachi13/customer-analytics

The data contains the following information:
1. ID: ID Number of Customers.
2. Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,E.
3. Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.
4. Customer care calls: The number of calls made from enquiry for enquiry of the shipment.
5. Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).
6. Cost of the product: Cost of the Product in US Dollars.
7. Prior purchases: The Number of Prior Purchase.
8. Product importance: The company has categorized the product in the various parameter such as low, medium, high.
9. Gender: Male and Female.
10. Discount offered: Discount offered on that specific product.
11. Weight in gms: It is the weight in grams.
12. Reached on time: It is the target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.

## Preparation
1. Python
2. Library : pandas, seaborn, matplotlib, plotly express

## Data Cleansing
The data does not contain major issues (No missing values and duplicated rows)

## Data Understanding
### Statistical Summary
The are no extreme values in the dataset and mostly features have symetrical distribution 

### Univariate Analysis
Visually analyze each columns : outlier can be found in 2 features and there are also 2 features that have skewed distribution

### Multivariate Analysis
Analyze multiple feature. So that we can see the correlation for each feature : there are no significant correlation for each variables. i.e we can use all variable for modelling process (if needed)

## EDA findings
1. The data does not contain major issues (no missing values and duplicated rows).
2. There are no extreme values for numerical features.
3. 5 features look normal and 2 features are indicated skewed, and also 2 features have an outlier.  
4. Mostly shipments type is 'ship' and in total 59.67% shipments has not reached on time and 40% of customers give bad rating (below the average).
5. There are no significant correlation for each features.
6. Discount_offered have positive correlation with Reached on Time or Not, and also Weights_in_gms have negative correlation with Reached on Time or Not.
7. Regardless of what product importance, the products are delivered late nonetheless
