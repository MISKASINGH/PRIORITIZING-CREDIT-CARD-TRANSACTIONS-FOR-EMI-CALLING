# PRIORITIZING-CREDIT-CARD-TRANSACTIONS-FOR-EMI-CALLING
Our objective is to help the Bank prioritize its Credit Card transactions for EMI calling. We had to come up with a way to predict the probability that any given transaction will be converted into EMI so as to reduce the cost by reducing the number of callers by finding out the most probable people who'll take EMI Credit card transactions.

# Problem statement
Bank A has a large base of savings account customers who have been cross sold Credit Cards. Bank A 
launched post transaction EMI as a proposition on their Credit Cards. However, conversion rates 
through digital campaigns were low. So, Bank A set up a call center where agents would call 
customers and sell post transaction EMI. 
However, Bank A soon realized that while this led to an increase in conversion rates of post 
transaction EMI, the cost too was on the higher side. Bank A then decided to only call customers 
who were more likely to convert their transactions into EMIs. This would enable the Bank to have 
fewer agents dedicated to EMI calling, thereby reducing the cost.
Your objective is to help the Bank prioritize its Credit Card transactions for EMI calling

# Datasets
You have been provided with a random sample of 50,000 Credit Card transactions 
“case_study_devdata.zip”, along with a flag (target_variable) – henceforth known as “development 
data”. Transactions that have been converted to EMI have target_variable = 1. You have also been 
provided with several independent variables. These include transaction attributes (amount, 
merchant etc.), card attributes (credit limit, product type etc.), previous history on the Card (spends 
on the card in the last few months, previous EMI conversion history etc.), savings account attributes 
(balances that the customer maintains in their savings account) and bureau attributes (kind of 
products the customer holds on the bureau). 
You have also been provided with another random sample of 30,000 Credit Card transactions 
“case_study_validation.zip” with the same set of input variables, but without target_variable. This 
will be referred to going forward as “validation data”.
Lastly, you have been provided with the data dictionary
