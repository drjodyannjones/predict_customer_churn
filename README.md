# Customer Churn Prediction

Customer Churn is an important metric for subscription-based businesses. Customer churn is the segment of your customer base that has stopped subscribing to your service or product. This is an important metric for businesses because it costs more to obtain a new customer than it is to retain current ones. Therefore, it is the goal of every subscription-based business to get their customer churn rate as close as possible to 0%. In this project, I analyzed a telecommunications company dataset consisting of 7,143 samples and 21 features from Kaggle.com. 

The ‘Churn’ feature is the target variable, and carries a label of ‘Yes’ indicating customers that have suspended their subscription and ‘No’ indicating customers that have continued their service. I trained several classification models in order to predict the likelihood of a customer churning or not, including: 1) logistic regression, 2) ensemble algorithms, and 3) boosting algorithms. I performed the following data preprocessing steps: 1) All categorical variables that were not ready for model training were transformed to dummy variables, 2) All numerical variables were scaled in order to account for differences in magnitude. 

The final model reported an overall weighted F1 score of 68%. If you have any questions or comments about the model, please feel free to reach out to me at jasjones82@gmail.com. For further information about the dataset, please visit https://www.kaggle.com/blastchar/telco-customer-churn. Thank you for reading.


