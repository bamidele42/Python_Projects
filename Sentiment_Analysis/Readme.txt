# Sentiment Analysis Project

This folder contain Sentiment Analysis Projects of the 2023 Presidential Elections in Nigeria and Random tweets of Nigerian at a moment in time(December 2022) to be specific, both project dataset were scrapped from twitter the popular social media platform.

## Pre-requisites
 - Python
 - twint library(Twint ia an advanced Twitter scraping tool written in Python that allows for scraping Tweet from Twitter profiles without using Twitter's API.
 - nltk
 - textblob library
 - pandas, matplotlib, seaborn, and jupyter notebook
 - Power BI (for interactive visualization)

## Getting Started (Sentiment Analysis of tweets before the 2023 Nigerian Presidential Election)

This project uses the twint library to scape tweets from twitter, you can get similar result with other open source libraries.

## Getting Started (Nigerians Random tweets at a given moment)

I used the city parameter of twint to get tweets for all the cities in Nigeria by iterating over a list of cities. The `City` parameter works with one city at a time.

	### Note: Not all devices usually have their location turn on, so the reason for this approach