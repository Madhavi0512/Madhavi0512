# Credit Card Fraud Detection Streamlit App
       
This project is a web application built using Streamlit to detect credit card fraud based on user input and analyze a dataset of credit card transactions. The app allows users to explore fraud-related data, predict fraudulent transactions, and evaluate different machine learning models.

## Overview
This project is a machine learning-powered web application built using Streamlit to detect and predict fraudulent credit card transactions. Credit card fraud detection is a critical challenge in the finance industry, where the goal is to accurately identify fraudulent transactions from legitimate ones in real-time, minimizing financial losses and protecting users.
## Key Features
1. **Data Exploration and Visualization**:

   The app allows users to interactively explore a dataset of credit card transactions, which typically includes transaction amount, time, and whether a transaction is fraudulent or not.
Users can visualize patterns in the data, such as the distribution of fraudulent vs. non-fraudulent transactions, using graphs and charts.</br>
2. **Fraud Detection Prediction**:
   
   The core functionality of the app is to predict whether a transaction is fraudulent based on user inputs. The prediction is made using machine learning models trained on historical transaction data.
The app provides real-time predictions by taking user-specified transaction details and predicting whether the transaction is suspicious or safe.</br>
3. **Machine Learning Models**:
   
   The app implements various machine learning algorithms such as K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression to classify transactions as fraudulent or non-fraudulent.
These models are trained on labeled datasets where fraudulent and legitimate transactions are identified, and they are optimized for high accuracy and minimal false positives.</br>
4. **Model Evaluation and Comparison**:
   
   The app allows users to evaluate the performance of different models using various metrics, such as accuracy, precision, recall, F1-score, and AUC-ROC.
Users can compare which models perform best in identifying fraud while minimizing the risk of falsely flagging legitimate transactions.

## About Dataset

  The dataset used for this project contains transactions made by credit cards. It includes a highly imbalanced set of observations, where fraudulent transactions are a small fraction of the total.
  ### Features:
- **V1-V28**: Principal components obtained via PCA.
- **Amount**: Transaction amount.
- **Time**: Time elapsed from the first transaction.
- **Class**: Fraud status (0 for non-fraud, 1 for fraud).
  Modeling and Evaluation ¶
## machine learning models:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
  
For each model:

   -Train on the imbalanced dataset and again on resampled dataset.
   
   -Evaluate performance using confusion matrices.
   
   -Compare results based on evaluation metrics.
### Libraries:

   -Numpy , Pandas , Seaborn , matplotlib , Streamlit , sklearn

   

          



  
