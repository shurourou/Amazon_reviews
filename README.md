# Amazon Review Sentiment Analysis 
**Objective:** To classify Amazon customer reviews as positive or negative using natural language processing (NLP) and machine learning.
Several traditional machine learning models were compared with DistilBERT, and DistilBERT was selected as the final model based on its superior test performance.

## Dataset
- **Source:** [Amazon Reviews Dataset — Kaggle](https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset)
- **File:** `Amazon_Reviews.csv`

## Workflow
1. Reading Dataset
2. Text Preprocessing
3. Splitting Data into Train (75%), Validation (10%) and Test (15%) Sets
   - Balancing Traning Data with RandomUnderSampler
4. Text Representation (TF-IDF)
5. Model Selection
   (a) Support Vector Machines (SVM)
   (b) Logistic Regression
   (c) Multinomial Naive Bayes
   (d) Random Forest
   (e) Decision Tree Classifier
6. Model Evaluation
7. SVM Model
8. EXTRA Model - Deep Learning Model - DistilBERT Model

