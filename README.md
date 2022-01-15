# Scraping historical tweets without Twitter API

This repo contains one notebook where I'm using snscrape for collecting historical tweets.   

What you need:

    Python 3.8

What you don't need:

    a Twitter Developer Account

For a research project related to public discourse about results on international large scale assessments I needed to scrape historical tweets, going back all the way to the begining of Twitter. This is how I discovered snscrape, a wonderful tool, easy to setup and use.

I didn't find snscrape from the start, initially I was reading through the intricate details of Twitter Developer Account, application procedure, different levels of access, limits etc etc. But luckily a friend recommended snscrape and suddenly the task of collecting tweets became extremely easy.

Snscrape is a popular tool with social scientists for Tweets collection, at least in 2021. Apparently, it bypasses several limitations of the Twitter API.
The prettiest thing is that you don't need Twitter developer account credentials (like you do with Tweepy, for example)

<b>How to use this repo</b>:  
Open the Jupyter Notebook in this folder. You can clone it, download it or just read it here. There is also a link at the top of the Notebook which takes you to the same Notebook on Kaggle.

Contents of the notebook:

    Installing snscrape
    How to use snscrape
    Calling snscrape CLI commands from Python Notebook
    Using snscrape Python wrapper
    Tweets meta-information gathered with snscrape
    Dataset manipulation: JSON, CSV and Pandas DataFrame
    Basic exploration of our collected dataset of tweets
    Bonus: Publishing your Jupyter Notebook on Medium
    What next ? Sentiment analysis

