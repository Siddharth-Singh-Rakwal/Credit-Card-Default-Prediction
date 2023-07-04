# Machine Learning Project

## Credit Card Default Prediction 💳
The Credit Card Default Prediction project aims to develop a robust predictive model by analyzing factors like credit history, payment patterns, and employment stability to determine the likelihood of credit card users defaulting, aiding lenders in risk assessment and improved decision-making for sustainable credit card management.
- Got 88.86% Accuracy on this Project from Random Forest Regressor
#

[GitHub Project Link](https://github.com/Siddharth-Singh-Rakwal/Credit-Card-Default-Prediction)

[LinkedIN Post Link](https://www.linkedin.com/posts/siddharth-singh-rakwal-b385a8263_project-algorithms-data-activity-7081225967054000128-uFFb?utm_source=share&utm_medium=member_desktop)

#

## Problem Statement:
Financial threats are displaying a trend about the credit risk of commercial banks as the
incredible improvement in the financial industry has arisen. In this way, one of the
biggest threats faces by commercial banks is the risk prediction of credit clients. The
goal is to predict the probability of credit default based on credit card owner's
characteristics and payment history.

#
## Dataset Information
Our dataset ‘Default of Credit Card Clients Dataset’ consists of informations about transactions from April 2005 to September 2005 of 30000 clients who were credit holders in a bank in Taiwan. This dataset has binary response variable ‘default.payment.next.month’ that takes the value 1 if the corresponding client has default payment and 0 otherwise. Out of 30000 clients 6636(22.12%) were with default payment. There are 23 other independent or explanatory variables:

- ID: ID of each client
- LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary = credit)
- SEX: Gender (1=male, 2=female)
- EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown) MARRIAGE: Marital status (1=married, 2=single, 3=others)
- AGE: Age in years
- PAY_1: Repayment status in September 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months,9=payment delay for nine months and above)
- PAY_2: Repayment status in August 2005 (scale same as above)
- PAY_3: Repayment status in July 2005 (scale same as above)
- PAY_4: Repayment status in June 2005 (scale same as above)
- PAY_5: Repayment status in May 2005 (scale same as above)
- PAY_6: Repayment status in April 2005 (scale same as above)
- BILL_AMT1: Amount of bill statement in September 2005 (NT dollar)
- BILL_AMT2: Amount of bill statement in August 2005 (NT dollar)
- BILL_AMT3: Amount of bill statement in July 2005 (NT dollar)
- BILL_AMT4: Amount of bill statement in June 2005 (NT dollar)
- BILL_AMT5: Amount of bill statement in May 2005 (NT dollar)
- BILL_AMT6: Amount of bill statement in April 2005 (NT dollar)
- PAY_AMT1: Amount of previous payment in September 2005 (NT dollar)
- PAY_AMT2: Amount of previous payment in August 2005 (NT dollar)
- PAY_AMT3: Amount of previous payment in July 2005 (NT dollar)
- PAY_AMT4: Amount of previous payment in June 2005 (NT dollar)
- PAY_AMT5: Amount of previous payment in May 2005 (NT dollar)
- PAY_AMT6: Amount of previous payment in April 2005 (NT dollar)

#

## How It Works
The Credit Card Default Prediction project operates through the following three-step process to deliver accurate predictions:

- Data Collection: A comprehensive dataset is gathered, encompassing demographic information, credit history, payment patterns, utilization and balances, and employment stability, among other relevant factors.

- Model Training: Cutting-edge machine learning algorithms are utilized to analyze the collected data, identify meaningful patterns, and create a predictive model capable of assessing the likelihood of credit card users defaulting.

- Risk Assessment and Decision Support: Leveraging the trained model, the system enables financial institutions to assess default risks associated with individual credit card accounts. This information empowers lenders to make informed decisions, implement proactive measures, and manage credit risk effectively.

#

## Create a New Environment for the Project:

Using anaconda
```
conda create -p venv python==3.8
```
To acivate the environment
```
conda create venv/
```
#

## Git commands

Configuration
```
git config --global user.name "<your name>"
git config --global user.email "<mail id registered with github>"
```
Check status
```
git status
```
Check logs
```
git log
```
Add all new or modified files
```
git add .
```
Add or update specific file
```
git add <file name>
```
Commit changes
```
git commit -m "<commit message>"
```
Push the commited changes
```
git push <remote> <branch>
```
#

## Usage
The Credit Card Default Prediction project offers valuable insights and practical applications for various stakeholders involved in credit risk management and lending decisions. Here are a few examples of how the predictions generated by the project can be utilized:

- Financial Institutions and Credit Card Issuers: Banks, credit card companies, and other financial institutions can leverage the predictive model to assess the creditworthiness of individuals applying for credit cards. By evaluating the likelihood of default, they can make informed decisions on credit approvals, credit limits, and interest rates, ensuring responsible lending practices and minimizing potential losses.

- Risk Management: The predictive model can be integrated into risk management frameworks to identify high-risk credit card accounts. This enables financial institutions to proactively monitor and manage these accounts, implement tailored strategies to mitigate default risks, and allocate resources effectively for collection and recovery processes.

- Portfolio Management: Credit card issuers can utilize the predictions to evaluate the overall risk exposure of their credit card portfolio. By identifying segments with higher default probabilities, they can adjust their risk appetite, optimize portfolio diversification, and develop targeted marketing and customer retention strategies.

- Customer Service and Support: The predictions can assist customer service representatives in providing personalized support to credit card holders. By understanding the risk profile of individual customers, representatives can offer tailored advice, payment assistance programs, or financial counseling to help customers avoid default and maintain healthy financial habits.

- Regulatory Compliance: Financial institutions can utilize the predictive model to meet regulatory requirements related to responsible lending practices and risk management. The insights gained from the model can aid in demonstrating compliance with regulations, such as assessing and mitigating the risks associated with credit card defaults.

It is important to note that the predictions generated by the Credit Card Default Prediction project serve as a tool to assist decision-making processes and risk assessment. They should be used in conjunction with expert judgment and other relevant factors to make well-informed business decisions in the credit card industry.

#
