# Car-Price-Prediction-ML-Regression
End-to-end machine learning project to predict car prices using multiple regression models, feature importance analysis, and hyperparameter tuning.




📌 Project Overview

A Chinese automobile company plans to enter the US market and wants to understand the factors affecting car prices. This project builds and compares multiple regression models to identify the key variables influencing car pricing and to predict car prices accurately.

🎯 Business Objective

The goal is to model car prices using various independent variables so the management can understand pricing dynamics and adjust car design, features, and business strategy accordingly for the US market.

📊 Dataset

The dataset contains different types of cars sold in the American market along with their specifications such as engine size, horsepower, dimensions, fuel type, and more.

⚙️ Project Workflow

1️⃣ Data Loading & Preprocessing

    Loaded dataset using Pandas
    
    Handled missing values
    
    Converted categorical variables using One-Hot Encoding
    
    Feature scaling using StandardScaler
    
    Train–Test split

2️⃣ Machine Learning Models Implemented

The following regression algorithms were implemented and compared:

    Linear Regression
    
    Decision Tree Regressor ⭐
    
    Random Forest Regressor
    
    Gradient Boosting Regressor
    
    Support Vector Regressor

3️⃣ Model Evaluation Metrics

Models were evaluated using:

    R² Score
    
    Mean Squared Error (MSE)
    
    Mean Absolute Error (MAE)

📌 Best Model: Decision Tree Regressor
    -- It achieved the highest R² and lowest prediction errors.

4️⃣ Feature Importance Analysis

Using the Decision Tree model, the most important features affecting car price were identified:

- Engine Size

- Horsepower

- Curb Weight

- Car Width

- Car Length

These variables strongly influence car pricing.

5️⃣ Hyperparameter Tuning

- GridSearchCV was used to tune the Decision Tree model.
The tuned model showed better generalization and reduced overfitting.

🛠️ Technologies Used

* Python

* Pandas

* Seaborn

* Scikit-learn

* Matplotlib
* Numpy

📈 Outcome

This project successfully:

- Built multiple regression models

- Compared model performance

- Identified key factors affecting car prices

- Selected the best model for prediction


  

👩‍💻 Author

Vandana Vasudevan
