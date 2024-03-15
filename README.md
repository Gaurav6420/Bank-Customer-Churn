# Leveraging the efficiency of Ensembles forCustomer Retention
**-Research project by 
[Gaurav Bavdane](https://github.com/Gaurav6420) and
[Neha Bhujbal](https://github.com/nehabhujbal222) 

To attract more customers every bank comes up with new offers every day. Due to this a customer is highly likely to get churned if the user gets a better offer at another bank. To survive in this 
competition, banks need to be updated regarding the offers present in market as well as how much their customers are loyal to their services. Customer demographics and credit card usage details are 
significant parameters to analyze customer behavior in the banking sector. The approach discussed in this report helps to predict/flag the customers which are more likely to get churned. If this model is 
used by bank as an early signal, banks can innovation in the services offered which may help increase customer retention.

**Datasets used:**
**Credit Card customers** 10,000 customers unbalanced dataset(2 classes, 16% positive & 84negative) extracted from Kaggle https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data


**Architecture:**
![image](https://user-images.githubusercontent.com/66311371/116960644-a65fec00-acbe-11eb-86cd-c43d597bc5b2.png)

**A brief overview:**[Uploading bank.drawio…]()<mxfile host="app.diagrams.net" modified="2021-09-30T04:30:27.549Z" agent="5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.4606.61 Safari/537.36" etag="JsaymMSYV-iW4dW0sBPa" version="15.3.8" type="google"><diagram id="l91m1EJqdrBcgBoKvKoU" name="Page-1">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</diagram></mxfile>

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
