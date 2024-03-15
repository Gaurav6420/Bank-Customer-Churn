# Leveraging the efficiency of Ensembles for Customer Retention
**-Research project by** 
[Gaurav Bavdane](https://github.com/Gaurav6420) and
[Neha Bhujbal](https://github.com/nehabhujbal222) 

To attract more customers, every bank comes up with new offers every day. Due to this, a customer is highly likely to churn if they receive a better offer from another bank. To survive in this competition, banks need to stay updated regarding the offers present in the market, as well as understand how loyal their customers are to their services. Customer demographics and credit card usage details are significant parameters for analyzing customer behavior in the banking sector. The approach discussed in this report helps predict/flag customers who are more likely to churn. If this model is used by banks as an early signal, they can innovate in the services offered, which may help increase customer retention.

**Datasets used:**
**Credit Card customers** 10,000 customers unbalanced dataset(2 classes, 16% positive & 84negative) extracted from Kaggle https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data


**Architecture:**
![image](https://github.com/Gaurav6420/Bank-Customer-Churn/assets/58482510/e8a784f3-1bf0-42df-969e-ae4274b6e61a)

**A brief overview:**
1. The most important challenge in this research was that the data was highly unbalanced (16:84). To balance the data we used different sampling techniques such as SMOTE, Border-line SMOTE, Border-line SMOTE SVM, and ADASYN. On further result analysis Border-line SMOTE SVM gave the best results.
2. To increase the accuracy and to reduce the computational power we decided to only use the relevant feature. This was achieved by using various feature selection techniques Lasso, Recursive Feature Elimination (RFE), and Random Forest (RF). To retain the best features we combined and scored to select the top 10 most significant features.
3. For classification we used various machine-learning models like KNN, RF, XRT, Adabosst, GBM, and RF+XRT+Adaboost. The ensemble of all the best-performing models helped us score the highest accuracy.


Banks can run this model on the existing data to devise customized marketing strategies as well as predict future trends. In addition to this, majority of the customers that have
churned belong to the group having low income or lie in the 40-60 years age group. The bank should direct its marketing initiatives to retain these customers through incentives, promotional mails, etc., instead of focusing on attracting new customers; as the cost of finding new customers is much higher than that of retaining the existing ones.

Our work was **published in 2021 Fifth International Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud) (I-SMAC) by IEEE**. 
Do give it a read for a better understanding of our work.
https://ieeexplore.ieee.org/abstract/document/9640757

Feel free to contact us with any queries or suggestions regarding the project. :)
