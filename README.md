# Fraud-detection
Credit card fraud detection using unsupervised learning

# Situation:

The project focused on detecting anomalies in credit card transactions using machine learning models. The dataset comprised transactions made by European cardholders over two days in 2013, including fraudulent transactions. The primary goal was to predict whether a given transaction was fraudulent, addressing the growing issue of credit card fraud in the financial industry.

# Task:

The task was to develop and evaluate models for anomaly detection to accurately identify fraudulent transactions. This involved:
Conducting data analysis and preparation.
Implementing multiple machine learning models (Isolation Forest, Local Outlier Factor, Support Vector Machine (OneClassSVM)).
Utilizing Random Forest for feature selection to enhance model performance.
Comparing the performance of these models using various metrics to identify the most effective approach.

# Action:

Data Analysis and Preparation:

Conducted exploratory data analysis (EDA) to understand the distribution and characteristics of the data.

Normalized and scaled the features (Time and Amount) to ensure consistency and improve model performance.

Dropped less important features based on feature importance from the Random Forest model.

Model Implementation:

Isolation Forest: Trained the model to isolate anomalies based on the concept of random partitioning.

Local Outlier Factor: Utilized the local density of data points to identify outliers.

Support Vector Machine (OneClassSVM): Implemented a model to separate normal transactions from anomalies using a hyperplane in a high-dimensional space.

Feature Selection with Random Forest:

Used a Random Forest classifier to determine feature importance and selected the most significant features to improve model performance.

# Model Evaluation:

Evaluated models using metrics such as accuracy, F1 score, recall, and confusion matrix to determine their effectiveness in detecting fraud.
Compared the performance of all models to identify the one with the best recall value, aiming to minimize False Negatives and ensure that few fraudulent transactions are missed.

# Result:

Best Performing Model: The OneClassSVM model achieved the highest recall value, making it the most effective in identifying fraudulent transactions while minimizing False Negatives.
Random Forest for Feature Selection: This step improved the overall model performance by focusing on the most significant features.
