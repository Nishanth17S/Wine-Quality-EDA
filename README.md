🍷 Wine Quality Prediction using Machine Learning
📌 Overview

This project focuses on predicting red wine quality using machine learning techniques. It includes detailed Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and building a deep learning model using TensorFlow/Keras.

The goal is to identify the most influential chemical properties that determine wine quality and build a reliable predictive model.

📊 Dataset

Dataset: Red Wine Quality Dataset

Features include:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

Target Variable: Quality (score)

🔎 Exploratory Data Analysis

Statistical summary of features

Correlation heatmap

Distribution plots

Outlier detection

Feature importance insights

Key observations:

Alcohol and sulphates positively impact quality.

Volatile acidity negatively impacts quality.

⚙️ Data Preprocessing

Handling missing values (if any)

Feature scaling (Standardization)

Train-test split

Encoding target variable (if required)

🧠 Model Architecture

Deep Learning model using TensorFlow / Keras

Fully connected neural network

Activation functions: ReLU / Softmax

Loss Function: Categorical Crossentropy / Binary Crossentropy

Optimizer: Adam

📈 Model Evaluation

Accuracy Score

Loss Curve

Confusion Matrix

Classification Report

The model demonstrates strong predictive capability after proper feature scaling and tuning.

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

TensorFlow / Keras

🚀 How to Run

Clone the repository

git clone <your-repo-link>


Install dependencies

pip install -r requirements.txt


Run the notebook

jupyter notebook

📌 Project Highlights

End-to-end ML workflow

Clean EDA with visualizations

Deep learning model implementation

Performance evaluation and insights

📬 Future Improvements

Hyperparameter tuning

Model comparison with traditional ML algorithms

Deployment using Flask / Streamlit

Cross-validation

👤 Author

Nishanth S
