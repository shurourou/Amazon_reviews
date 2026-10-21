# Amazon Review Sentiment Analysis 
Hi everyone! This is my first project, where I explored how to use Python and natural language processing (NLP) to classify Amazon customer reviews as positive or negative.

## Live Demo
Try the sentiment analysis model here: [Live Demo on PythonAnywhere](https://shurou.pythonanywhere.com/)

Enter an Amazon review to see the model predict whether the sentiment is positive or negative.

## Dataset
- **Source:** [Amazon Reviews Dataset — Kaggle](https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset)
- **File:** `Amazon_Reviews.csv`
- **Task:** Binary sentiment classification (positive and negative reviews) 
- **Objective:** To classify Amazon customer reviews as positive or negative using natural language processing (NLP) and machine learning.

The dataset was cleaned and preprocessed before being used to train and evaluate the classification models.

## Workflow 
1. Reading Dataset
2. Text Preprocessing - lowercase, remove URL, HTML tags, etc...
3. Splitting Data into Train, Validation and Test sets
4. Balancing Traning data with RandomUnderSampler
5. Fit TF-IDF on balanced Training set; Transform Val & Test set
6. Model Selection
7. Model Evaluation



