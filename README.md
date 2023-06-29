# Advanced_Classification_-_Team_GM3_2301FTDS
## Notebook version control for the 2301_FTDS_TeamGM3_Advanced_Rergession predict team challenge

This repository contains the code and resources for the Classification Sprint challenge, where the goal is to create a machine learning model that can classify whether a person believes in climate change based on their novel tweet data. The challenge aims to provide companies focused on environmental impact and sustainability with valuable insights into public perception of climate change. The challenge can be found [here](https://www.kaggle.com/competitions/edsa-sentiment-classification), and the accompanying notebook serves as our entry.

## Problem Statement:

Many companies are built around lessening one’s environmental impact or carbon footprint. They offer products and services that are environmentally friendly and sustainable, in line with their values and ideals. They would like to determine how people perceive climate change and whether or not they believe it is a real threat. This would add to their market research efforts in gauging how their product/service may be received.

The task is to build a classification model that accurately predicts whether a person believes in climate change or not, based on their tweets. The dataset provided contains a collection of tweets from different users, which have been labeled as pro climate change, anti climate change, neutral, or factual news tweets. 

Providing an accurate and robust solution to this task gives companies access to a broad base of consumer sentiment, spanning multiple demographic and geographic categories - thus increasing their insights and informing future marketing strategies.

## Getting Started:
The repository contains the following resources:

* `profanity_en.csv` : A csv file containing common english curse words used in the data preprocessing
* `train.csv` : The data used to train our models. It consists of the tweet _sentiment_, _message_, and _tweetid_.
* `train.csv` : The data used to test our models by means of prediction. It consists of the tweet _message_, and _tweetid_.
* `FinalNotebook.ipynb` : The notebook in which the preprocessing and modelling takes place. This is also used to produce files for submission to the competition

  ### Prerequisites
The following libraries need to be installed, but can be done so by following the steps in the notebook:
* wordcloud
* contractions
* catboost
* xgboost
* comet_ml
* emoji
  
  ### Usage
  To reproduce the results or use the provided code, follow these steps:

1) Clone the repository: `git clone https://github.com/Kabous0017/Advanced_Classification_-_Team_GM3_2301FTDS.git`
2) Explore the Jupyter notebooks `FinalNotebook.ipynb` to understand the data preprocessing, feature engineering, and model development steps.

### Known Bugs
The notebook sometimes fails to render on GitHub, sue to the size and images contained within. If this is the case, please find a fully rendered version [here] (https://nbviewer.org/github/Kabous0017/Advanced_Classification_-_Team_GM3_2301FTDS/blob/e2210041ba9a2083b44f795fc00feba5a68fa145/FinalNotebook.ipynb)
