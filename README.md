# TweetClassifier: NLP-Driven Demographic Profiling

## Introduction

TweetClassifier is a research initiative exploring the feasibility of deducing demographic data such as gender and age from Twitter content. This project serves as a foundational study with potential implications for targeted marketing and audience understanding.

### -- Project Status: [Completed]

## Project Objective
- **Demographic Inference**: Experiment with NLP models to infer user demographics from tweets.
- **Methodological Framework**: Develop a preliminary methodology for data collection, labeling, and analysis to set the stage for future product development.

## Partner

Gratitude is extended to Intuition Intelligence Inc. and San Francisco State University, with a special nod to Prof. Cheung & Ozsen, for their invaluable contributions to this exploratory study.
- [Dr. Leyla Ozsen](https://www.linkedin.com/in/leyla-ozsen-9424a33/)
- [Dr. Rex Cheung](https://cob.sfsu.edu/directory/rex-cheung)

## Technologies and Methods

The study utilized Python, Twitter API, Tweepy, BERT, and a two-layer stacking model approach. The first layer of the model consists of various basic classifiers (weak learners), and the second layer combines their outputs to enhance prediction accuracy, demonstrating the potential for a scalable demographic prediction model.
![Stacking Model Visualization](image/example.png)

## Repository Contents

- [Gender Prediction Model](Notebooks/TweetClassifier.ipynb): Early-stage model development including preprocessing, analysis, and an innovative two-layer model architecture.
- [Twitter API Streamer ](Notebooks/TwitterStreamer.ipynb): Initial scripts for data collection.
- [Research Essay](Research_Essay.pdf): A detailed written analysis encapsulating the project's findings and methodological approach.

## Reflections

The project presents a promising start into the application of social media data towards understanding demographic trends. The two-layer ensemble model used here is a significant step in advancing NLP-driven demographic profiling.

## Data and Scripts Disclaimer

Please note, the original dataset for this project is not available. The scripts in this repository demonstrate our methodology but may differ from our original experiment in algorithms and parameters. They are intended to illustrate our model's structure and approach, without the capability to replicate the exact results.