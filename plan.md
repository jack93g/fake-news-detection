**Plan**

Stage 1: get and clean data

- aim for 20000 datapoints (10000 fake news and 10000 real)
- webscrape data from factchecking sites - snopes, politifact etc
- use premade datasets from kaggle etc
- bring all sources together into one dataset

Stage 2: data analysis & visualisation

- can look at which sources have the most fake news - eg trump, facebook etc
- which words are the 'fakest' and 'realest'
- which topics are the most common - eg politics, culture etc
- classify sources - mainsteam, non mainstream etc
- named entity regocnition - can identify key info from text and use it to classify the text
- use sentiment analysis and create word clous of top 50 negative words, top 50 positive words erc


Stage 3: prepare data for modelling - text transformation

- can use: NLP, countvectorizer, BERT, universal sentence encoder (best one according to abhi) 
- decide on whether to use headlines or text - can use cross validation and grid search for this

Stage 4: modelling

- decision trees
- logistic regression
- naive bayes?

Stage 5: presentation

- find some facts/stats about fake news



**articles/previous projects about fake news ml**

https://github.com/berkurka/Reddit-Classifier/blob/master/Notebooks/03%20Model.ipynb

https://github.com/edumunozsala/Intro-NLP-Text-Classification/blob/master/Intro_NLP_1_TFIDF_Text_Classification.ipynb

https://www.kaggle.com/ankitanikumbh/fake-news-detection

https://www.kaggle.com/devanshiipatel/fake-news-classification


**datasets**


https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset - dataset no good ?

https://github.com/KaiDMML/FakeNewsNet - doesn't have the news source (fb, daily mail etc)

https://github.com/nguyenvo09/fake_news_detection_deep_learning - downloaded snopes dataset

https://www.kaggle.com/arminehn/rumor-citation/data?select=politifact.csv - cant download for some reason

https://github.com/pmacinec/fake-news-datasets/tree/master/datasets





