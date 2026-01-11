🏠 House Price Prediction using Machine Learning


📌 Project Overview:
This project focuses on predicting house prices using supervised machine learning techniques.
The model is trained on the Kaggle House Prices – Advanced Regression Techniques dataset and demonstrates a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and prediction on new data.

🎯 Objective:
To build a regression model that accurately predicts house prices based on various housing features and to compare different machine learning models to improve performance.

📂 Dataset
Source: Kaggle – House Prices: Advanced Regression Techniques

Records: 1460

Features: 81

Target Variable: SalePrice

Note: The dataset is US-based. An India-like house configuration is mapped to available features only for demonstration of model usage.

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Google Colab

🔍 Project Workflow


1️⃣ Data Exploration (EDA)

Inspected dataset structure using df.info() and df.describe()

Visualized the distribution of house prices

Identified missing values and data types


2️⃣ Data Cleaning & Preprocessing

Dropped features with very high missing values

Imputed numerical features using median

Filled categorical missing values using appropriate strategies

Encoded categorical variables using One-Hot Encoding


3️⃣ Model Training

Two models were trained and compared:

Linear Regression (Baseline Model)

Random Forest Regressor (Final Model)


4️⃣ Model Evaluation

Evaluation Metric: R² Score

Linear Regression R²: ~0.64

Random Forest R²: ~0.89


5️⃣ Visualization

Distribution of target variable

Actual vs Predicted house prices

Feature importance using Random Forest


6️⃣ Prediction on New Data

Tested the trained model on a new, India-like house configuration

Applied the same preprocessing and feature alignment steps before prediction


📊 Results
The Random Forest Regressor significantly outperformed Linear Regression, achieving an R² score of approximately 0.89, indicating strong predictive performance.

🚀 How to Run the Project

Open the notebook House_Price_Prediction.ipynb in Google Colab or Jupyter Notebook

Upload the dataset file train.csv

Run the notebook cells sequentially from top to bottom


🧠 Key Learnings


Handling missing values based on data context

Importance of feature encoding for machine learning models

Comparing baseline and advanced models

Visualizing model performance for better interpretation

📌 Conclusion
This project demonstrates a complete machine learning regression pipeline, from data preprocessing to model evaluation and real-world prediction. It highlights the effectiveness of ensemble models like Random Forest for complex, non-linear datasets.

👩‍💻 Author
Malavika Anilkumar
B.Tech (AI & DS)
Aspiring Data Science & Machine Learning Engineer
