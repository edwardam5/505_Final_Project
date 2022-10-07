# 505_Final_Project

## Installation

 To use this project, first clone the repo on your device using the command below: 
 
 git init
 
  git clone https://github.com/edwardam5/505_Final_Project.git
    
    
## Project Intro/Objective 
The purpose of this study is to predict whether an American Bank of Commerce's
customer will churn or not. For this study, it was hypothesized that at least one of 
the seven classification algorithms of Logistic Regression, Naive Bayes, Neural 
Network, K-Nearest Neighbor (KNN), Decision Tree, Random Forest, and Linear 
Discriminant Analysis will result in a model that predicts a customers churn status of
high risk of churning or low risk of churning. More specifically, a secondary 
hypothesis is that the best predictor will be the Linear Discriminant Analysis (LDA) 
model, based on the accuracy and precision score being greater than eighty percent. 
The raw dataset was sourced from Kaggle. The predictor variables observed in this 
study include: credit score, country, gender, age, tenure, account balance, product
number, possession of a credit card, whether the customer is an active member, and the 
estimated salary of the customer. The study determined that the best model was the 
Random Forest model, which had an accuracy of 85% and a precision score of 87%. 
Further research regarding the precision and sensitivity of the model could be 
evaluated using additional predictors such as employment status and highest level of
education. 

## Contributors 
- Jonathan Yoon 
- Amin Fesharaki
- Anusia Edward

## Methods Used 
- Data Mining 
- Predictive Modeling 
- Machine Learning 
- Data Visualization 

## Technologies 
- Python 

## Project Description 
The project is a classification project in which the study aims to predict whether a
bank’s customer will churn or not.

#### Dataset Description 
This dataset was sourced from Kaggle as a raw csv file. The total number of variables for
this dataset is twelve, which includes the following variables: customer_id, credit_score,
country,gender, age, tenure, balance, products_number, credit_card, active_memeber, 
estimated_salary,and churn. The variable customer_id indicates the member’s account 
number, while the variablecredit_score indicates a member’s credit score. The variable 
country indicates the member’s country of residence, while the variable gender indicates 
the sex of the bank member. The variableage indicates the age of the bank member, while 
the variable tenure indicates the amount of time the bank member has had a bank account
with ABC Bank. The variable balance indicates the member’s account balance, while the 
variable products_number indicates the number of products from the bank. The variable 
credit_card indicates whether a member has a credit card, while the variable 
active_memeber indicates whether a member is actively using their account. The variable
estimated_salary indicates the salary of an account holder, while the variable churn 
indicates whether the member is still with the bank. The variables are comprised of 
binary, ordinal, and numerical variables. There are a total of 10,000 records within this
dataset.

#### Background 
The growth of a company is heavily dependent on unit economics, which refers to the direct
revenues and costs of a particular business. Churn, the measure of the number of customers who
leave a company in a given period, is one aspect of unit economics. The loss of customers, or
churn, negatively impacts the growth of a company. It should be noted that there are two forms of
customers who churn, voluntary and involuntary churning. Voluntary churning refers to a
customer actively deciding to end their membership based on the service they received from a
particular company. Essentially, it refers to overall customer satisfaction. Involuntary churning
refers to members who churn because of customer delinquencies such as payment failures.

#### Current Situation 
As of current, ABC International Bank, like many banks, is facing the dilemma of finding ways to
retain current members to maintain overall profitability. The key crisis in terms of current
members is the rate of churn. Voluntary churn based on customer satisfaction levels is an
avoidable loss. Customer satisfaction is key to retaining customers; therefore, improving overall
revenue can be achieved through analysis of customers in terms of looking into which attributes
are indicative of a customer that has a low-churn probability. Through research on the bank’s
members, those that are more likely to continue with the bank can be targeted by the marketing
team via email campaigns, while those that are high-churn risk and lower revenue can be avoided
to save on resource expenses. This will help create a balanced customer base, that will allow the
bank to optimize its resources and minimize churn. In terms of addressing involuntary churning,
the way in which to address it would be to determine which subset of customers are likely to churn
and determine if it is profitable to expend resources on those members.

### Hypothesis 
For this study, it was hypothesized that at least one of the seven classification algorithms of Logistic Regression, Naive Bayes, Neural Network,
K-Nearest Neighbor (KNN), Decision Tree, Random Forest, and Linear Discriminant Analysis will result in a model that predicts a customers churn 
status of high risk of churning or low risk of churning. More specifically, a secondary hypothesis is that the best predictor will be the Linear 
Discriminant Analysis (LDA) model, based on the accuracy and precision score being greater than eighty percent. 
