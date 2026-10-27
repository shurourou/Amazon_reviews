# Amazon Review Sentiment Analysis 
**Objective:** To classify Amazon customer reviews as positive or negative using natural language processing (NLP) and machine learning.
Several traditional machine learning models were compared with DistilBERT. Although the SVM and DistilBERT models achieved similar performance, the SVM model was selected as the final model.

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

