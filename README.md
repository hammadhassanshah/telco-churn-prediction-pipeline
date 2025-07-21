**Telo Churn Prediction Pipeline**
An end-to-end ML pipeline to predict customer churn for a telecom company. It covers data cleaning, feature engineering, model training, inference, and reporting.

1. Data Preprocessing
   * Handle missing values
   * Encode categorial & scale numerical features
   * Preserve cleaned data & scales
  
2. Model Training
   * Train LightGBM Classifier
   * Evalulate via ROC-AUC, confusion matrix, classification report
   * Save trained model
  
3. Inference
   * Load saved model & predict churn on unseen data
  
4. Reporting
   * Visualize feature importance
   * Summarize insights & churn patterns

**Dataset**
Telo Communication Churn Dataset
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
