******🍷 Wine Quality Prediction using Machine Learning******


This project aims to predict the quality of wine based on physicochemical tests using various machine learning algorithms.

The dataset contains red and white wine samples with numerical features such as acidity, sugar, pH, and alcohol content.

The target variable is a quality score ranging from 0 to 10, rated by wine tasters.


**📂 Dataset Overview**


Source: UCI Machine Learning Repository – Wine Quality Dataset

Samples: ~6,500 rows (combined red and white wine)

Features: 11 physicochemical attributes including:

Fixed acidity,

Volatile acidity,

Citric acid,

Residual sugar,

Chlorides,

Free sulfur dioxide,

Total sulfur dioxide,

Density,

pH,

Sulphates,

Alcohol,

Target: quality (Score: 0 to 10)


**🎯 Objective**


To build a machine learning model that can accurately predict wine quality based on its physicochemical properties,

and evaluate which algorithms perform best on this classification task.


**🧹 Data Preparation**


Missing Values: Checked and confirmed none.

Outlier Treatment: Detected and handled using IQR method and z-score for features like alcohol and sulphates.

Normalization: MinMaxScaler applied to scale numerical features.

Class Balance: The quality scores are imbalanced (most are 5, 6). Addressed using techniques like class binning or SMOTE for balanced training.


**🤖 Models Used**


Several classification models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Ada Boost Classifier

XGBoost


**📊 Evaluation Metrics**


Accuracy

Precision

Recall

F1-Score

Confusion Matrix


**🧠 Skills Applied**


Exploratory Data Analysis (EDA)

Supervised Machine Learning

Model Evaluation and Comparison

Feature Scaling and Engineering

Handling Imbalanced Data

Visualization with matplotlib and seaborn


