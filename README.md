# ARCVIL CHURN PREDICTION


![image](git url)


## 1. INTRDUCTION
ArcVil is a telecommunication company that is US-based. Its aim is to provide efficient and affordable info-communication services to its customers. In recent years, the has been stiff competition in the telecommunication industry. Due to the many competitors offering various produccts in the telecommunication industry, customers have a variety of telecommunication options to chose from. Arcvil therefore wants to maintain its customers base. This is because, the cost of acquiring new customers is higher than the cost of maintaining them. When customers migrate to competitiors, Arcvil's profit is also affected. Management of Arcvil want a predictive model that can accurately predict customers who have the potential to churn

## 2. BUSINESS PROBLEM
### The Problem statement
There are many telecommunication companies that have come up. As a result, customers have a variety of choices to chose from. As a result, competition is stiff and Arcvil wants to maintain its customer base. This is because, the cost of acquiring new customers is higher than the cost of maintaining them. The management of Arcvil has requested for a prediction model to help them determine which customers are likely to churn.

## OBJECTIVES.
### Main Objective.
To come up with a predicitve model that will assist the Arcvil accurately predict customers who will churn

### Specific Objectives.
Come up with various models to predict customers who will churn and choose the best based on performance metrics
Select the best model for predicting using evaluation metrics

## 3. NOTEBOOK STRUCTURE
The notebook is [here](git url)
The python notebook is structured as follows:
1. Data understanding
2. Exploratory Data Analysis
3. Data preprocessing
4. Data Modelling and evaluation
5. conclusions and recommendations

## 4. DATA UNDERSTANDING
### The Data
The data used in this project was downloaded from [Kaggle](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/discussion/235073) but it was for a prediction competition for [CrowdANALYTIX](https://www.crowdanalytix.com/contests/why-customer-churn). The dataset consists of one csv file. It contains 20 columns and  3333 records. Out of this 3333 record, there are 483 customers who churned and the remaining 2850 are non-churners. The column names are: 
-state
-account length
-area code
-phone number
-international plan
-voice mail plan
-number vmail messages
-total day minutes
-total day calls
-total day charge
-total eve minutes
-total eve calls
-total eve charge
-total night minutes
-total night calls
-total night charge
-total intl minutes
-total intl calls
-total intl charge
-customer service calls
- Lastly, to validate this data reference was made to an article by [IRJET](https://www.irjet.net/archives/V3/i4/IRJET-V3I4213.pdf)

### Data Preparation
The following process was followed in order to prepare our data for modeling: -checked for duplicated or missing value (our data set did not contain any) -derived new features (total charges) in order to get an overview of how much churner spend vs non-churners. -preprocess data (this involved converting categorical data to appropriate format using LabelEncoder, normalsing the numerical columns using MinMax Scaler and oversampling our data using SMOTE to handle imbalances data between churners and non-churners).

### Exploratory Data Analysis
EDA explanation.

![image](git url)


### Modeling
The following modeling techniques were used:
Logistic regression
RandomForest Classification
DecisionTree Classification
After evaluating the performance of the three models, RandomForest performed better than the rest. It was then tuned using max_depth which even showed slight improvement on the evaluation metrics



![image](url for git)



## 5.CONCLUSIONS 
-
## 6.RECOMMENDATIONS
- 


## 7.REPOSITORY GUIDE
Below are the links for the varoious documentations for this project
- Data Set [here](https://www.crowdanalytix.com/contests/why-customer-churn)
- Data Report [here](https://docs.google.com/document/d/10iNv7Ajx8poz9PXEvR0HqUwtP92XJbQdmwehJqBPvU8/edit#)
- Notebook [here](https://github.com/madivolil5/CHURN-COMMUNICATION/blob/main/churn%20prediction.ipynb)
- Presentaion slides [here]([url](https://www.canva.com/design/DAFXbR6ippQ/MxOiewNURlboaxrXaBawSQ/edit?utm_content=DAFXbR6ippQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton))
