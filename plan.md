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

https://towardsdatascience.com/fake-news-detection-with-machine-learning-using-python-3347d9899ad1

https://www.kdnuggets.com/2017/04/machine-learning-fake-news-accuracy.html

https://towardsdatascience.com/developing-a-data-science-model-to-predict-fake-news-184c25a13cb8

https://github.com/jasminevasandani/NLP_Classification_Model_FakeNews

https://github.com/aldengolab/fake-news-detection - here there are some tips about name replacement - could be useful



**datasets**


https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset - dataset no good ?

https://github.com/KaiDMML/FakeNewsNet - doesn't have the news source (fb, daily mail etc)

https://github.com/nguyenvo09/fake_news_detection_deep_learning - downloaded snopes dataset

https://www.kaggle.com/arminehn/rumor-citation/data?select=politifact.csv - cant download for some reason

https://github.com/pmacinec/fake-news-datasets/tree/master/datasets





