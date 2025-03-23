# EDA_PROJECTS
# DATA ANALYSIS & MACHINE LEARNING MODELS OF KAGGLE DATASETS
## This repository contains various Exploratory Data Analysis (EDA) projects on different datasets. The goal of these analyses is to extract insights, detect patterns, and understand the underlying structure of the data. Each dataset has been processed using statistical summaries, visualizations, and feature analysis techniques.

# 📌1. Breast Cancer Dataset & Project Overview
  - Filename:-[breast-cancer.csv](breast-cancer.csv)
  - Objective: Analyze the characteristics of tumors and identify patterns in malignant and benign 
     cases.
    
## 📊 Exploratory Data Analysis (EDA)
  -**EDA Notebook:** [Breast_cancer.ipynb](EDA_BREAST_CANCER.ipynb)
  - Statistical summaries of dataset features
  - Data visualization using histograms, pair plots, and correlation heatmaps
  - Feature selection and preprocessing

## 🏗️ Feature Engineering 
  - Data cleaning (handling missing values, duplicates)
  - Encoding categorical features(Label Encoding)
  - Scaling numerical features (StandardScaler)

## 🤖 Machine Learning Models Implemented 
  - **Logistic Regression** 
  - **Decision Tree Classifier**

## 🔮 Future Enhancements
  - Implement additional models (SVM, Random Forest, etc.)
  - Hyperparameter tuning for improved performance
  - Deploy the best-performing model as a web app



# 📌2. Traffic Accident Dataset & Project Overview
  - Filename: [Traffic Accidents Dataset](https://www.kaggle.com/datasets/oktayrdeki/traffic-accidents)
  - Objective: Identify patterns in road accidents based on various factors such as time, 
    location, and cause.

## 📊 Exploratory Data Analysis (EDA)
 -**EDA Notebook:** [Open in Google Colab](https://colab.research.google.com/drive/13m3MmWTOtcj4l0XxeiUfj8uAL-EdRLpD#)
 - Statistical summaries of dataset features
 - Data visualization using histograms, pair plots, box plots, and correlation heatmaps
 - Feature selection and preprocessing

## 🏗️ Feature Engineering
  - Data Cleaning (handling missing values, duplicates)
  - Encoding categorical features(Label Encoding)
  - Scaling numerical features(StandardScaler)

## 🤖 Machine Learning Models Implemented
  -  **Gradient Boosting Regressor** 
  -  **XGBRegressor**

## 🔮 Future Enhancements
  - Implement ensemble models (Random Forest, Gradient Boosting) to improve prediction accuracy.
  - Explore deep learning models for accident prediction.
  - Develop a dashboard for interactive data visualization.
  - Perform geospatial analysis to identify high-risk accident zones.


 # 📌3. Wine Quality Dataset & Project Overview
   - Filename: [WineQT.csv](WineQT.csv)
   - Objective: Analyze the chemical composition of wine and its relationship with quality  
     ratings.

## 📊 Exploratory Data Analysis (EDA)
 -**EDA Notebook:** [Wine_Quality.ipynb](EDA_WINE.ipynb)
 - Statistical summaries of dataset features.
 - Data visualization using histograms, pair plots, box plots, and correlation heatmaps.

## 🏗️ Feature Engineering
  - Data Cleaning (handling missing values, duplicates)
  - Scaling numerical features(MinMaxScaler)

## 🤖 Machine Learning Models Implemented
  -  **Logistic Regression** 
  -  **Random Forest Classifier**
  -  **Support Vector Machine(SVM)**

## 🔮 Future Enhancements
  - Create new features based on existing chemical properties to improve predictive power.
  - Extract interaction terms between variables (e.g., acidity and alcohol content).


# 📌4. Credit Card Dataset & Project Overview
  - Filename: [credit_card_fraud_dataset.csv]( credit_card_fraud_dataset.csv)
  - Objective: Explore fraudulent and non-fraudulent transactions and identify key indicators of 
    fraud.

## 📊 Exploratory Data Analysis (EDA)
   -**EDA Notebook:** [Credit_Card.ipynb](EDA_CC.ipynb)
   - Class distribution analysis (fraud vs non-fraud)
   - PCA (Principal Component Analysis) for dimensionality reduction
   - Correlation between features
   - Fraud transaction trends and patterns

## 🏗️ Feature Engineering
  - Data Cleaning (handling missing values, duplicates)
  - Encoding categorical features(Label Encoding)
  - Scaling numerical features(StandardScaler)

## 🤖 Machine Learning Models Implemented
  -  **Logistic Regression** 
  -  **Random Forest Classifier**
  -  **XGBClassifier**

## 🔮 Future Enhancements
  - Apply anomaly detection techniques such as Isolation Forest and Autoencoders.
  - Use time-series analysis to detect evolving fraud trends.
  - Improve feature selection and engineering for better classification performance.
  - Develop an interactive dashboard for real-time fraud monitoring.


# Performance Evaluation 
 ## **For Classification Models**
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
 ## ** For Regression Model **
   - Mean Squared Error
   -  R² score

# 🛠 Technologies Used
  - **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost)
  - **Jupyter Notebook** for interactive analysis
  - **Google Collab** for traffic accident EDA

# How To Use
 1. Clone this repository:
   `git clone https://github.com/chhavviii/EDA_PROJECTS.git`
 2. Navigate to the repository:
    `cd EDA-Projects`
3. Open and run the Jupyter Notebook and google colab notebook on each dataset to explore the 
   analysis.

# Dependencies 
 `pip install pandas`
 `pip install numpy`
 `pip install matplotlib`
 `pip install seaborn`
 `pip install scikit-learn`

