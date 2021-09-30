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

* Dependent variables: current formula brand.

* Independent variables: first purchase brand, email OR, CTR, coupon redemption rate, enrollment type, enrollment age, baby age, breastfeed type, hospital zone.​

* Machine Learning Models: Logistic regression, decision tree, Artificial Neural Network.​

# 5. Raw Data



Note that the dataset has been modified and resamples due to the non-disclosure agreement.

## Variable intepretation:
* Current brand: "1" represents our brand, and other values represent other brands.
* First purchase brand: "1" represents our brand, and other values represent other brands.
* Email OR (open rate): the nubmer of emails opened/the number of emails have been sent to a person
* Email CTR (open rate): the nubmer of emails clicked/the number of emails have been sent to a person
* Coupon redemption rate: the nubmer of coupon redeemed/the number of emails have been sent to a person
* Enrollment type: the source from which a person enroll to our program (Digital Self Enrollment, Co-registered)
* Enrollment age: the age of the baby when the parent enrolled in our program
* Baby age: the age of the babay when the parent took the survey 
* Breastfeed type: "1" represents our hospital zone, and other values represent other brands.
* Hospital zone: "1" represents our hospital zone, and other values represent other brands.


# 6. Data cleaning

* Remove the records with “null” value.
* Manipulate certain columns. (e.g. set the ones with current brand as MJN equal to 1 , other brands as 0).
* Scale each column (ranged from 0 to 1).

