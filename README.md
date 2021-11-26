
# **fake-news-detection-machine-learning**


![fake news image](./images/fake-news.jpg
)

---

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#project-files">Project Files</a></li>  
    <li>
      <a href="background">Background</a>
      </ul>
    </li>
    <li><a href="#workflow">Workflow</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#libraries">Libraries</a></li>
  </ol>
</details> 

---
<!-- Project Files -->
## **Project Files**  


`images`: contains all the images used in the project.    
`files`: contains all CSV data files.  
`news_scraping.ipynb`: web scraping news sites with beautiful soup and selenium 
`data_cleaning.ipynb`: carrying out data cleaning with regex etc  
`EDA.ipynb`: exploratory data analysis and visualisations of data
`sentiment_analysis.ipynb`: NLP with textblob and vader  
`fake_news_prediction.ipynb`: using different ML algorithms to predict if text is fake or real


---
<!-- background -->
## **Background**

In recent years media consumption habits have changed due to the spread of the internet. More people get their news from digital sources such as social media and search engines than ever before. News articles from such sources unfortunately often have very little to do with the truth. The aim of this project is to use natural language processing techniques and machine learning algorithms to see if we can detect such fake news articles.  

See my [presentation](https://docs.google.com/presentation/d/1li1ZAZ_O9XeMkK0UOUZBNHxEL7FeGjLBQtk9KQ_xtrY/edit#slide=id.geea67f8950_0_1241) here
 for further details!



<!-- Workflow -->
## **Workflow**

- Scraped articles from real news sites and combined with dataset of fake news from kaggle. 
- Cleaned the text. Removed URLS, HTML tags & punctuation.
- Preprocessed data - removed stopwords and lemmatised the text.
- Converted text to vectors using the TF-IDF vectoriser.
- Applied different machine learning algorithms including, SVM, Random Forest & logistic regression to the data.
- Created a python function which takes a news article as a user input and then vectorises the text and predicts whether it is fake or real using support vector machine.


---

<!-- Results -->
## **Results**

- SVM was the best model overall 
- Accuracy score: 0.96
- F1 score: 0.96

### Some further findings  




Most common words from the fake news articles.

![fake news](./images/fake.png
)

Most common words from the real news articles

![real news](./images/real.png
)


---
<!-- Libraries -->
## **Libraries**

- [Pandas](https://pandas.pydata.org/docs/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org)
- [Sklearn](https://scikit-learn.org/stable/)
- [NLTK](https://www.nltk.org)
- [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/#)
- [Selenium](https://selenium-python.readthedocs.io)
- [Textblob](https://textblob.readthedocs.io/en/dev/)
