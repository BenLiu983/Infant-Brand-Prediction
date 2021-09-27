# Infant-Brand-Prediction
Predicting consumers' current brand choice by Machine Learning algorithms

# 1. Introduction

This project is based on a dataset from mulitple data sources, including CDP (customer data platform), D2C (direct to customer/Shopify), NITFS (national infant and toddler feeding survey). The dataset is from a infant brand in Canada, and it has been modified. 

# 2. Objectives

* Investigate the features that impact the current infant formula brand for a mom
* Forecast the probability of a caregiver uses MJN as their formula.


# 3. Data Sources

The samples are selected from from multiple internal databases (with common key), and the time period is from 2019 Jan to 2020 Dec. 

# 4. Methodology

* Dependent variables: current formula brand.​

* Independent variables: first use brand, email OR, CTR, coupon redemption rate, enrollment type, enrollment age, baby age, breastfeed type, hospital zone.​

* Machine Learning Models: Logistic regression, decision tree, Artificial Neural Network.​

# 5. Data cleaning

* Select or calculate the variables from the data lake.
* Utilize the common key “Individual ID” to link 2 data sources.
* Remove the records with “null” value.
* Manipulate certain columns. (e.g. set the ones with current brand as MJN equal to 1 , other brands as 0).
* Scale each column (ranged from 0 to 1).

