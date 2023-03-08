# EDA AND LOGISTIC REGRESSION

#### VARIABLES

* RowNumber: a unique identifier for each record.
* CustomerId: a unique identifier for each customer.
* Surname: surname of the customer.
* CreditScore: credit score of the customer.
* Geography: country of the customer.
* Gender: gender of the customer.
* Age: age of the customer.
* Tenure: number of years for which the customer has been with the bank.
* Balance: balance in the customer's account.
* NumOfProducts: number of bank products the customer is using.
* HasCrCard: indicates whether the customer has a credit card (1) or not (0).
* IsActiveMember: indicates whether the customer is an active member (1) or not (0).
* EstimatedSalary: estimated salary of the customer.
* Exited: indicates whether the customer has exited the bank (1) or not (0).

## Descriptions

[EDA_and_logistic_efficient.ipynb](./EDA_and_logistic_efficient.ipynb) | 
The method first loads the data into a Pandas dataframe and then performs some basic EDA operations such as missing value checks, statistical summary, target column distribution, and correlation matrix. The categorical features are then encoded, and the encoded features are concatenated with the original data. Lastly, it divides the data into training and testing sets and uses the training data to create a Logistic Regression model. It then predicts the target on the test data and evaluates the model using the confusion matrix and classification report.


## Steps

* Import the churn data from customers into a pandas dataframe.
* Conduct exploratory data analysis by verifying the head of the data, the shape of the data, for missing values, and charting the distribution of numerical and categorical variables.
* Split the data into training and test sets before one-hot encoding categorical variables and building a logistic regression model. Use the logistic regression model to predict client turnover and evaluate its performance with the categorization report.