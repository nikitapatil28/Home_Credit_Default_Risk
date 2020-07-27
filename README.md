# Home_Credit_Default_Risk-
Predict risk of getting Home credit loan defaulted
Using Data set https://www.kaggle.com/c/home-credit-default-risk

Aim: Home Credit provides loan to all kind of population including unbanked people to provide positive and safe borrowing experience. They want to identifiy potiential customer who will be able to repay the loans.

Datasets:
•	application_{train|test}.csv
	  This is the main table, broken into two files for Train (with TARGET) and Test (without TARGET).
    Static data for all applications. One row represents o application_{train|test}.csv
	  This is the main table, broken into two files for Train (with TARGET) and Test (without TARGET).
	  Static data for all applications. One row represents one loan in our data sample.

• bureau.csv
    All client's previous credits provided by other financial institutions that were reported to Credit         Bureau (for clients who have a loan in our sample).
 
• bureau_balance.csv
    Monthly balances of previous credits in Credit Bureau. This table has one row for each month of history     of every previous credit reported to Credit Bureau

• POS_CASH_balance.csv
    Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with       Home Credit.
    
• credit_card_balance.csv
    Monthly balance snapshots of previous credit cards that the applicant has with Home Credit.

• previous_application.csv
    All previous applications for Home Credit loans of clients who have loans in our sample.

• installments_payments.csv
    Repayment history for the previously disbursed credits in Home Credit related to the loans in our           sample.

Models:
1. Logestic Regression - 0.671 accuracy
2. Random Forest - 0.678 accuracy


Reference: https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction
