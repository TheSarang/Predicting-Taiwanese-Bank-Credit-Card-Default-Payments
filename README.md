Table of Contents:
+ [Fintech Hackathon Project](#Fintech_Hackathon_Project) </br>
+ [Data Set](#Data_Set) </br>
+ [Hackathon Result and Links](#Links) </br>
## <a name="Fintech_Hackathon_Project"></a> Fintech Hackathon Project
FIntech Hackathon Project from April 21th, 2018

## <a name="Data_Set"></a> Data Set 

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

There are 24 features:

**Demographic Information**
- ID: ID of each client
- LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
- SEX: Gender (1=male, 2=female)
- EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
- MARRIAGE: Marital status (1=married, 2=single, 3=others)
- AGE: Age in years

**Repayment Status for past 6 months**

**(-1 = pay duly, 1 = payment delay for one month, 2 = payment delay for two months,..., 9 = payment delay for nine months and above)**

- PAY_0: Repayment status in September, 2005 
- PAY_2: Repayment status in August, 2005 (scale same as above)
- PAY_3: Repayment status in July, 2005 (scale same as above)
- PAY_4: Repayment status in June, 2005 (scale same as above)
- PAY_5: Repayment status in May, 2005 (scale same as above)
- PAY_6: Repayment status in April, 2005 (scale same as above)


**Amount of bill statement for past 6 months**
- BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
- BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
- BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
- BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
- BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
- BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)

**Amount of previous payment for past 6 months**
- PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
- PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
- PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
- PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
- PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
- PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)

**Target Variable**
- default.payment.next.month: Default payment (1=yes, 0=no)

***

## <a name="Links"></a> Hackathon Result 

**Won first place with ROC = 0.78 and Recall = 0.73:**
https://www.credential.net/2u3vyimu/sso?code=4894

**Presentation:**
https://prezi.com/p/u7gonyvlmslg/fintech/
