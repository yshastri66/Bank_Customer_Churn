# Bank_Customer_Churn_dataset

## Probelm statement
The problem statement here is to predict whether a customer will leave the bank or retain in the bank based on the famous kaggle dataset which is <b>bank_customer_churn_dataset</b>.<br>
I tried with <b>Artificial Neural Networks , Logistic regression , K nearest neighbours algorithm and Random forest algorithm </b> for this dataset after visualizing the dataset and performing some of the feature engineering tasks. Out of the all above models <b>Random Forest </b>yields 86% accuracy. Since the dataset is imbalanced, we can consider this accuracy as best only. 
### Dataset contains following columns :
<ul>
  <li>CustomerId</li>
  <li>Surname</li>
  <li>CreditScore</li>
  <li>Geography - country of customer</li>
  <li>.Gender</li>
  <li>Age</li>
  <li>Tenure - Total number of years with bank</li>
  <li>Balance
  <li>NumOfProducts - Number of products or services utilising from bank</li>
  <li>HasCrCard - Utilising credit card or not ( Card - 1 , No card - 0 )</li>
  <li>IsActiveMember - Metric defining the member on the basis of his/her transactions (Active - 1 , Inactive - 0 ) </li> 
  <li>EstimatedSalary</ul>
   <br>
   <b>Based on above columns we are predicting Exited column :</b><br>
  <b>Exited - Left bank or not ( left bank - 1 , retained by bank - 0 )</b>
