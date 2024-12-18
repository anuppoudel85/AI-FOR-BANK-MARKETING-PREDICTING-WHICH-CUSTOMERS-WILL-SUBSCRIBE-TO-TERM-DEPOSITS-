# AI-FOR-BANK-MARKETING-PREDICTING-WHICH-CUSTOMERS-WILL-SUBSCRIBE-TO-TERM-DEPOSITS-
# Description
Term deposits are a major source of income for commercial banks. A term deposit is a cash
investment held at a financial institution. Your money is invested for an agreed rate of
interest over a fixed amount of time, or term, to earn interest. The bank has various outreach
plans to sell term deposits to their customers such as email marketing, advertisements, and
telephone marketing. Telephone marketing campaigns remain one of the most effective ways
to reach out to people. However, they require huge investment as large call centers are hired
to execute these campaigns. Hence, it is crucial to identify the customers who are most likely
to invest beforehand so that they can be specifically targeted via phone calls.
You are provided with client data such as: client age, their job type, their marital status, etc.
Along with client data, you are also provided with information about any previous calls made
to a client, such as duration of call, day and month of call, etc. Given this information, your
task is to predict if a client will subscribe to term deposit
# Datasets
The datasets for this assignment come from direct marketing campaigns (phone calls) of a
commercial banking institution. You are provided with the following two files:
1. train.csv: Use this dataset to train machine learning models. This file contains all the
clients’ data and previous call details (if any) as well as values of the target variable (class
attribute) “subscribed”. You must train your models using this file.
2. test.csv: Use the trained models to predict whether another set of clients will subscribe
to term deposits.
Dataset Attributes - Here is the description of all the variables/attributes:
id: unique client ID
age: age of client
job: type of job of client
marital: marital status of client
education: education level of client
default: client has credit in default?
balance: client’s total balance in savings accounts (note: a negative balance is usually valid)
housing: client has housing loan?
loan: client has personal loan?
contact: client’s contact communication type (categorical: 'cellular', 'telephone')
day: day of last contact
month: month of last contact
duration: last contact duration, in seconds
campaign: number of contacts performed during this campaign to the client
pdays: number of days that passed by after the client was last contacted from a previous
campaign (-1 means client was not previously contacted)
previous: number of contacts performed before this campaign for this client
poutcome: outcome of the previous marketing campaign to the client
subscribed - Output variable (class attribute) - has the client subscribed to a term deposit?
