# Twitter User Gender Prediction

This early-stage exploration project conducts the methods to apply public Twitter data for user gender prediction, 
including data collection, preparation, and delivers a classification baseline model. 
The research is supported by Intuition Intelligence Inc. and San Francisco State University.

#### -- Project Status: [Completed]

## Project Objective
There are two main objects for the project:
1) Utilize user's public text data for gender predict
2) Define appropriate data collection, labeling, and preparation methods for future research

### Partner
* Intuition Intelligence Inc.
* San Francisco State University -- Especially thanks Prof. Chung & Ozsen

### Methods Used
* Inferential Statistics
* Text Mining, NLP
* Data Visualization
* Machine Learning
* Stacking Model

### Technologies
* Python
* Colab, JupyterNotebook
* Tweepy, TwitterAPI
* Pandas, BERT, Scikit-learn
* LucidChart, Tableau

## Project Description
### Data source:
Self-collected data from Twitter API:  
Raw data size: 400k x 100 attributes  
Actual training size: 2,029 x 12 attributes (After labeled and feature selection)

### Assumption:
1) Twitter users’ writing style is different by gender groups. This fundamental assumption allows 
   us to utilize text features for our prediction modeling.  
2) All Twitter users have an equal willingness to disclose demographic data in their Twitter account profile. 
   This assumption ignores the sample bias for our manually labeling process.

## Getting Started
The repository includes: 
  1. [Twitter API Streamer ](Notebooks/Twitter_app_streamer.ipynb) - Data collection
  2. [Gender Prediction Model](Notebooks/gender.ipynb)
  3. [Presentation Slides](https://github.com/Liam-LT/Twitter_User_Gender_Age_Detection/blob/master/Slides/TwitterProject.pdf)

