
![Logo](https://www.freepnglogos.com/uploads/twitter-logo-png/twitter-logo-with-birds-symbol-icon-24.png)


# Coronavirus Tweet Sentiment Analysis

COVID-19 is caused by SARS-CoV-2, the coronavirus that emerged in December 2019. COVID-19 was declared a global pandemic on March 11, 2020. COVID-19 can be severe and has caused millions of deaths worldwide and lasting health problems in some who have survived the illness. In this project, I have built a sentiment analysis model using tweets extracted from Twitter posted on coronavirus. By analyzing, cleaning and pre-processing all the tweets and feeding the resultant data into an ML model, we can classify the sentiment of any tweet on coronavirus into positive, negative or neutral classes.

## Install

This project requires Python and the following Python libraries installed

* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [TextBlob](https://textblob.readthedocs.io/en/dev/)
* [NLTK](https://www.nltk.org/)
* [PIL](https://pillow.readthedocs.io/en/stable/)
* [Wordcloud](https://pypi.org/project/wordcloud/)
* [scikit-learn](https://scikit-learn.org/stable/)

We also need to have software installed to run and execute a Jupyter Notebook.

We can install the [Anaconda](https://www.anaconda.com/) distribution of python
which already has most of the above packages and more included or we can also run the 
whole notebook on google colab without going through the process of installing all the
libraries locally in our machine.


## Code

The main code is provided in the `Coronavirus_Tweet_Sentiment_Analysis.ipynb`
notebook file. We will also require the dataset
`Coronavirus Tweets.csv` in which all the tweets along with a few other
information is stored.
## Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) 
and run one of the following commands:

```
ipython notebook Coronavirus_Tweet_Sentiment_Analysis.ipnyb
```
or
```
jupyter notebook Coronavirus_Tweet_Sentiment_Analysis.ipnyb
```
or open with Jupyter Lab
```
jupyter lab
```
This will open the Jupyter Notebook software and project
file in our browser
## Data

We are working with a dataset named `Coronavirus Tweets`, it is a csv file.
The Coronavirus Tweets dataset holds a total of 41157 records and all of these 
datapoints have 6 features each.

### Features

    1.  Username : The username of the person on twitter
    2.  Screenname : The screenname of the person on twitter
    3.  Location : The location from where the tweet was tweeted
    4.  TweetAt : The date of the tweet
    5.  OriginalTweet : The tweet itself unfiltered
    6.  Sentiment : The sentiment of the tweet our target variable
  

### Target Variable : `Sentiment`
## 🛠 Algorithms Used
Lemmatization , Naive Bayes , Logistic Regression , Stochastic Gradient Descent and Support Vector Machine


## Authors

- [@Yash1289](https://github.com/Yash1289)


## 🚀 About Me
I'm an aspriring data scientist who loves to `deeply` work with data


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaurabh-pandey-69484921a/)



