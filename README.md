# Credit-Fraud-Detection
The purpose of this study is to build a model that can effectively detect fraudulent transactions and help financial institutions protect their customers from potential losses due to fraudulent activity, as well as a credit card fraud detection model that works effectively with "unseen" or "out-of-distribution" data. Unseen data is data that differs dramatically from training data, replicating real-world events in which the model meets transactions it has never seen before.
Financial Institutions (Banks) are continuously dealing with fraud activities, and this is increasing over time because of the multiple options that customers have nowadays to process payments. At the same time, it's getting more difficult to prevent fraudulent activities, because of the various methods available for scammers to access private information. This is the main reason for this study, to be able to create a model in order to predict real-world and real-time fraud transactions.
To achieve the following project, we are going to use different large datasets so we can create a robust model for better prediction results. For that, a total of 5 datasets are considered, some of them with extra columns that are not relevant to the analysis. For that reason, we are going to keep only the ones that they share in common. Some of the datasets contain time but not date, however, in the dataset description, we can find the data considered for the data collection, based on that, we are going to create a date column, which will help for a better approach in the analysis, especially for time series.
### The first dataset considered is a dataset of a total of 284807 rows, and 31 columns, from where we are going to keep only 3 columns: Time, Amount, and Class, and based on the date description we have we are going to create a column for date. 
### The second dataset contains a total of 94682 rows and 20 columns. From where we will keep only 4 columns: DOMAIN, TIME1, TOTAL_TRN_AMT, and TRN_TYPE. As we have in the description the dates considered for this data collection, we will add a column with the Date in order to perform a better analysis. 
### The third Dataset contains a total of 339607 rows and 15 columns, from which we are going to keep only 3: trans_date_trans_time, amt, is_fraud.
### The fourth Dataset contains 6362620, and 11 columns, we are going to keep only 4 columns: step(time), type, amount, isFraud	and create date column. 
### Dataset We are going to consider it later for testing in real-world the model, with a dataset unseen for the model, since is not labeled as a fraudulent or legit transaction, this is going to help to identify how the model performs in an unseen scenario. 


Dataset 1
https://www.datacamp.com/workspace/datasets/dataset-python-credit-card-fraud
-Date 2019-01-01 00:00:44 to 2020-12-31 23:59:24
-339607 rows 

Dataset 2
https://usmart.io/org/deloitte/discovery/discovery-view-detail/17881c8f-4fa2-4832-99ea-eb2f4033eac2
Data updated: 19/3/2018
-6362619 rows
-step: step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 743 (30 days simulation).

Dataset 3 
https://data.gov.ie/dataset/cbm03-detailed-daily-card-payments/resource/bf7cfa88-5d7b-4139-a3f9-a7216d9fd07e?inner_span=True
Date: 01/03/2020 to 01/02/2021
 -9464 rows 
