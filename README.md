# Email Classification

In the age of information overload, effective management of emails has become a critical challenge. Individuals and organizations receive a vast amount of emails daily, making it essential to automate the process of sorting and categorizing these emails for efficient handling. The aim of this project is to develop a robust email classification system using machine learning techniques. The system will analyze the content of
emails and accurately categorize them into predefined classes such as spam, promotions, updates, and important communications. I used kaggle dataset "https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv" 


**sample dataset**


<img width="879" alt="image" src="https://github.com/dakshnakumar/YBI-Project/assets/81346958/907192bd-21f9-43ea-a399-3407e7e29288">



**Graph that shows ,how many times word "THE" is occuring in the email**


<img width="398" alt="image" src="https://github.com/dakshnakumar/YBI-Project/assets/81346958/adad0c3a-9863-4107-9b2f-2f5227011ed8">

Did all the preprocessing technique to create prefect dataset for model training 
Trained 3 different models. the models are Randome forest , logistic regression , Decision tree to classifiy spam or not spam. The dataset is split in the ratio of 70:30 for training and testing 
Model accuracies are:

**Logistic Regression: 0.965** ,
**DecisionTree: 0.924** ,
**Random Forest: 0.967** 

overall , **Logistic Regression and Random Forest** are performing well for this dataset
