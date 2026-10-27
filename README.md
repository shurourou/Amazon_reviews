# Amazon Review Sentiment Analysis 
**Objective:** To classify Amazon customer reviews as positive or negative using natural language processing (NLP) and machine learning.
Several traditional machine learning models were compared with DistilBERT. 

## Live Demo
Enter a review to predict its sentiment: https://shurou.pythonanywhere.com/ 

## Dataset
- **Source:** [Amazon Reviews Dataset — Kaggle](https://www.kaggle.com/datasets/dongrelaxman/amazon-reviews-dataset)
- **File:** `Amazon_Reviews.csv`

## Workflow
1. Reading Dataset
2. Data Cleaning and Sentiment Categorization
3. Text Preprocessing
4. Splitting Data into Train (75%), Validation (10%) and Test (15%) Sets
   - Balancing Traning Data with RandomUnderSampler
5. Text Representation (TF-IDF)
6. Model Selection
   - Support Vector Machine (SVM)
   - Logistic Regression
   - Multinomial Naive Bayes
   - Random Forest
   - Decision Tree Classifier
7. Model Evaluation
8. SVM Model
9. EXTRA Model - Deep Learning Model - DistilBERT Model

## Model Selection
Although DistilBERT achieved slightly better test performance, SVM was selected as the final model due to its lower computational requirements and simpler deployment. 

SVM Model: 
              precision    recall  f1-score   support

   negative        0.97      0.95      0.96      2153
   positive        0.88      0.94      0.91       873

   accuracy                            0.95      3026
   macro avg       0.93      0.94      0.93      3026
weighted avg       0.95      0.95      0.95      3026

DistilBERT: 
       precision    recall  f1-score   support

   negative        0.99      0.95      0.97      2153
   positive        0.89      0.96      0.93       873

   accuracy                            0.96      3026
   macro avg       0.94      0.96      0.95      3026
weighted avg       0.96      0.96      0.96      3026
