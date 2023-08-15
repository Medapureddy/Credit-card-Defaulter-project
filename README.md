# Credit-card-Defaulter-project
**Problem Statement**: Predict whether a customer is defaulting credit payment for the next month

The findings of the project aim to assist financial institutions by addressing the below: 
**1) Risk Management:**
  To proactively reduce credit limit of users based on their profile and mitigate losses.
**2) Customer Rentention:**
  Rentaining customers by providing tailored incentives to low-risk customers using customer segmentation. 

This dataset has over 30,000 observations and 24 features & contains information on default payments, demographic factors, credit data,history of payment, and bill statements of credit card clients

• **Source:** https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
 UCI Machine learning repository

The notebook consisits of the following parts:
1) Exploratory Data Analysis
2) Data cleaning and further exploration
3) Building a base model
4) Feature Engineering
5) Building ML model using various algorithms and comparing them
6) Conclusion

**Features:**

**LIMIT_BAL**: **Continuous.** Credit Limit of the person.
**SEX**: **Categorical**: 1 = male; 2 = female
**EDUCATION**: **Categorical**: 1 = graduate school; 2 = university; 3 = high school; 4 = MARRIAGE: 1 = married; 2 = single; 3 = others
**AGE**: num. **Continuous**
**PAY_0,PAY_2 to PAY_6**: **Categorical** :-
2:Payment made in full and on time
-1: payment made in full but past the due date
0: payment of minimum amount was made
1: payment amount less than the minimum amount due
2: payment amount is between the minimum amount due and the full amount due 
3: payment amount is between one and two months late
4: payment amount is between two and three months late
5: payment amount is between three and four months late
6: payment amount is between four and five months late
7: payment amount is between five and six months late
8: payment amount is between six and seven months (or more) late. 
**BILL_AMT1 to BILL_AMT6:** Amount of bill statements.
**PAY_AMT1 to PAY_AMT6:** Amount of previous payments 
**Target:**
**Default** **Categorical**
0:The Person will not be in the defaulter for the next month
1: The Person will be in the defaulter list for the next month
