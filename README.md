# Company-Bankruptcy-
To predict whether company goes for bankruptcy 

Problem Explanation
 
   To predict whether a company is showing symptoms of getting bankrupt or not. The 
problem statement is to develop a prediction model which will predict whether a 
company can go bankrupt or not.

The dataset consists of multiple financial ratio columns such as:

Return on Assets (ROAs)
Gross Profits
Operating & Net income and Expenses
Cash flows
Taxes
Growth rate
Debt
Turnover, Revenue, Liability, etc.

Target column is Bankrupt with outcome as 0 or 1
(0 is No, 1 Yes)


2. Load data
Importing all the libraries like numpy, pandas, seaborn and more..
Loading the dataset using Pandas.

3. EDA
Checking the shape of the dataset and information using 
  shape
  info()
Total  6819 rows and 95 columns 

Checking if any duplicate values are presented – NO duplicate records

Checking NULL values or Missing values – NO null values 

Checking for imbalance data

The labelled data of Bankruptcy is plotted and it is not balanced.
It is highly imbalanced dataset as only 3.2% of total data is of class label 1 (Bankrupt).
The pie chart describes the Bankruptcy where
 0 is No
 1 is YES

