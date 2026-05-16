# Fraud Detection

This project aims to detect fraudulent credit card transactions by analyzing transaction data and applying machine learning techniques to identify, visualize, and predict fraudulent patterns. The project focuses on handling the highly imbalanced nature of financial data—where fraudulent transactions are rare compared to legitimate ones—using advanced techniques to enhance detection accuracy.


## Core Project Components

- **Data Analysis & Visualization:** Analyzing transaction features such as amount, time, and location to understand patterns.
- **Data Preprocessing:** Cleaning data, handling missing values, scaling features using tools like StandardScaler or RobustScaler, and addressing class imbalance.
- **Balancing Techniques:** Employing methods like SMOTE (Synthetic Minority Over-sampling Technique), random oversampling, or undersampling to improve model performance on minority class (fraud) detection.
- **Machine Learning Modeling:** Implementing supervised and unsupervised learning algorithms to classify transactions as genuine or fraudulent.


## Machine Learning Models Used

- **Logistic Regression:** A popular, interpretable, and effective model for binary classification tasks, often used for its speed and reliability in predicting fraud probability.
- **Random Forest:** An ensemble method combining multiple decision trees to identify non-linear relationships among variables, consistently performing well in identifying fraud patterns.
- **XGBoost/Gradient Boosting:** Known for high performance on tabular data, offering high accuracy for real-time fraud detection systems.
- **Support Vector Machine (SVM):** Effective for high-dimensional datasets and identifying complex boundaries between classes.
- **Neural Networks/Autoencoders:** Utilized for anomaly detection by learning the baseline of normal behavior and identifying statistically unusual transactions.


## Methodology & Workflow

- **Data Collection & Cleaning:** Loading transactional data and removing noise.
- **Feature Engineering:** Creating new, meaningful features (e.g., time of day, distance from previous location) to improve model prediction.
- **Training and Testing Split:** Splitting data to ensure models are trained on historical data and tested on unseen data.
- **Evaluation Metrics:** Using appropriate metrics to evaluate imbalanced datasets, including Precision, Recall, F1-Score, and ROC-AUC curve.
- **Real-Time Detection:** Developing a framework for immediate flagging or blocking of suspicious transactions.


## Commonly Used Datasets

- **PaySim Simulator Data:** Simulates mobile money transactions to create balanced scenarios for training.
- **European Cardholder Data:** A classic, highly imbalanced dataset used to test fraud detection algorithms (e.g., from Kaggle).


## Expected Outcomes

The project aims to achieve a high-accuracy, scalable, and adaptable solution that reduces false positives and effectively identifies fraudulent activities in real-time banking environments.


## Link For Dataset:
https://drive.google.com/file/d/1Y1Sd5VEQx2AWTuONZdbA0fS3xgYUFpID/view?usp=drive_link
