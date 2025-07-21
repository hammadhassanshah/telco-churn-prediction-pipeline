**Telo Churn Prediction Pipeline**
An end-to-end ML pipeline to predict customer churn for a telecom company. It covers data clearning, feature engineering, model training, inference, and reporting.

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

**Folder Structure**
CHURN/
├── 01_data_cleaning.ipynb
├── 02_model_training.ipynb
├── 03_model_inference.ipynb
├── 04_reporting.ipynb
├── data/
│   ├── raw/
│   └── processed/
└── models/

**Dataset**
Telo Communication Churn Dataset
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
