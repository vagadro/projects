**ML Project-SPAM DETECTION**

**Web app**: https://sms-vagadro.herokuapp.com/

**Overview:** Spam detection is one of the most common and the earliest problem which was solved using Machine Learning and Artificial Intelligence. One of the most common application of which is to classify if an email is a spam or not and thus trasfer into "Spam" folder in our emails. Another similar application is to classify a text message into "Spam" and not "Spam" and directly trasfer into a specified folder in our phones. This is useful in preventiing frauds, overburdering mailboxes etc and can be very useful in real life. 

In this project, I have tried to identify weather a particular new SMS is a potential Spam message or not. This is done using classical classfication algorithms using Machine learning. 

**Dataset used:** https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
For training the model, we have used a dataset of approximately 5000 messages, classfied into "Spam" and "ham". This dataset is obtained from kaggle. 

**Approach:** A very simple approach was followed to build the model and the results were deployed using Streamlit app running on heroku server.
- Data Loading
- EDA: identification of outliers, correlation between features etc
- Data Cleaning and preprocessing: Since we are dealing with text data, NLTK library alongwith NLP techniques were used to pre process data and create some features 
- Model Building: since the data is in text and since in order to use the same in modelling, few Text 2 vector techniques like BOW, TFIDF were used. Multiple classification models were build like SVC, KNN, Naive Bayes, Random Forest, Logistic Regression, XGBoost, GBDT, ADA Boost, Voting Classfier, Ensemble modelse etc in this step and accuarcy and precision were noted for each model on train and test dataset. Clas
- Final Model: Multinomial Naive Bayes model was finalised due to high precision and accuracy
- Deployment: Model deployed using Streamlit framewok using heroku server

In case you want to check out the same visit:  https://sms-vagadro.herokuapp.com/

**Few test cases:**
SPAM:
- congratulations you won 1000. call on this number to get your prize
- you could win 5000 from credit card or loan. Reply to collect

Not Spam:
- Hello, are you coming to office today?
- Do know who won the match yesterday? I had my bets on India

Best,

Deepak Rawat

Linkedin: linkedin.com/in/deepak-rawat-183316b5

----------------------------------------------------------------------------------------------------------------------------------------------------------------


