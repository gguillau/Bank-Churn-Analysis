Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
### Background
This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

## Objective
Predict whether a customer will leave the bank soon. Build a model with the maximum possible F1 score.
Achieve an F1 score of at least 0.59. Check the F1 for the test set.
Additionally, measure the AUC-ROC metric and compare it with the F1.

## Data Description
* Features
  * RowNumber — data string index
  * CustomerId — unique customer identifier
  * Surname — surname
  * CreditScore — credit score
  * Geography — country of residence
  * Gender — gender
  * Age — age
  * Tenure — period of maturation for a customer’s fixed deposit (years)
  * Balance — account balance
  * NumOfProducts — number of banking products used by the customer
  * HasCrCard — customer has a credit card
  * IsActiveMember — customer’s activeness
  * EstimatedSalary — estimated salary
* Target
  * Exited — сustomer has left
  
## Libraries Used
- Pandas
- Matplotlib.pyplot
- scipy.stats
-numpy
- sklearn  

## Models Evaluated
* DecisionTreeClassifier
* RandomForestClassifier
* LogisticRegression

