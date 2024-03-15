# Leveraging the efficiency of Ensembles for Customer Retention
**-Research project by 
[Gaurav Bavdane](https://github.com/Gaurav6420) and
[Neha Bhujbal](https://github.com/nehabhujbal222) 

To attract more customers, every bank comes up with new offers every day. Due to this, a customer is highly likely to churn if they receive a better offer from another bank. To survive in this competition, banks need to stay updated regarding the offers present in the market, as well as understand how loyal their customers are to their services. Customer demographics and credit card usage details are significant parameters for analyzing customer behavior in the banking sector. The approach discussed in this report helps predict/flag customers who are more likely to churn. If this model is used by banks as an early signal, they can innovate in the services offered, which may help increase customer retention.

**Datasets used:**
**Credit Card customers** 10,000 customers unbalanced dataset(2 classes, 16% positive & 84negative) extracted from Kaggle https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data


**Architecture:**
![image](https://github.com/Gaurav6420/Bank-Customer-Churn/assets/58482510/e8a784f3-1bf0-42df-969e-ae4274b6e61a)


1. While selecting keywords from each review one of the main tasks is to 
remove stop words without losing the prime sentiment of 
the review. This has been achieved by selecting **specific POS 
tags (adjective, adverb, verb, noun)**  instead of explicitly removing 
all the stop words and performing **lemmatization using gensim.**
2. Further, **TF-IDF vectorizer** is used to 
score each word and highlight the word’s relevance in each 
review. 
3. For classification two of the most commonly used 
classifiers, **Naïve Bayes** and **SVM** are used. We also trained a 
**Feed Forward Neural Network** and all the results are 
empirically discussed. 
4. We have employed **Cross Validation** 
and **GridSearch** to get the best model that fits the data. 


This process of sentiment analysis will help gauge the bigger 
picture rather than scrutinizing each review to drive deeper 
insights and help organizations formulate effective business 
strategies.

Our work got **published in International Research Journal of Engineering and Technology (IRJET) Volume 8, Issue 4,  April 2021**. 
Do give it a read for a better understanding of our work.
https://www.irjet.net/archives/V8/i4/IRJET-V8I4854.pdf

Feel free to contact us with any queries or suggestions regarding the project. :)
