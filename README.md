# Credit Score Classification
Classifying customers based on their credit scores helps banks and credit card companies immediately to issue loans to customers with good creditworthiness. A person with a good credit score will get loans from any bank and financial institution. 
This project involves building a credit scoring model using various features of customers such as occupation, annual income, number of bank accounts, number of credit cards, interest rates, and others. The goal is to predict whether a customer is likely to default on their loan payment based on their credit score.
### Data
The dataset used for this project is a synthetic dataset created using Faker library in Python. It has 100000  rows and 27 columns.

### Exploratory Data Analysis
The exploratory data analysis involved visualizing the categorical features to check if they affect the credit scores. The following features were analyzed:

- Occupation
- Annual income
- Monthly in-hand salary
- Number of bank accounts
- Number of credit cards
- Interest rates
- Number of loans taken by the person
- Average number of days delayed for credit card payments
- Number of delayed payments
- Outstanding debt
- Credit utilization ratio

The analysis showed that having more bank accounts or credit cards does not positively impact the credit score. On the other hand, having more than 3-5 credit cards or bank accounts will negatively impact the credit score. Similarly, maintaining an average interest rate of 4-11% is good for the credit score, while having an interest rate of more than 15% is bad for the credit score.
The analysis also showed that delaying credit card payments for 5-14 days from the due date will not impact the credit score negatively. However, delaying payments for more than 17 days will have a negative impact on the credit score. Similarly, delaying 4-12 payments from the due date will not affect the credit score, but delaying more than 12 payments will negatively impact the credit score.
### Conclusion
The credit scoring model built using the dataset can be used to predict whether a customer is likely to default on their loan payment based on their credit score. The exploratory data analysis showed that various features such as occupation, annual income, number of bank accounts, and credit cards affect the credit score. Maintaining an average interest rate of 4-11% is good for the credit score, while having an interest rate of more than 15% is bad for the credit score. The analysis also showed that delaying credit card payments for more than 17 days from the due date or delaying more than 12 payments will negatively impact the credit score.
