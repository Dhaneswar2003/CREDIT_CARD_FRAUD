CREDIT CARD FRAUD DETECTION
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This project is part of my internship at CodSoft, where I developed a machine learning model to detect fraudulent credit card transactions. The model is trained using a balanced dataset of credit card transactions, and it employs a Random Forest classifier to achieve high accuracy in detecting fraud.

Features:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Data Loading and Exploration: The dataset is loaded and explored to understand its structure and characteristics. We focus on the Class column, where 0 represents non-fraudulent transactions and 1 represents fraudulent ones.

Data Preprocessing: The dataset is imbalanced, so we balance it by undersampling the majority class (non-fraudulent transactions) to match the number of fraudulent transactions.

Model Training: A Random Forest classifier is trained using a pipeline that includes data scaling and classification.

Model Evaluation: The model's performance is evaluated using metrics like precision, recall, and f1-score, achieving a high accuracy rate.

Model Deployment: The trained model is serialized using pickle for potential deployment in a production environment.

Key Files:
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
creditcard.csv: The dataset used for training and testing the model.

model.pkl: The trained Random Forest model.

fraud_detection.ipynb: The Jupyter notebook containing the entire workflow, from data loading to model evaluation.

Tools and Technologies:
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Python: For data manipulation and machine learning.

Pandas: For data handling and processing.

Scikit-learn: For machine learning model training and evaluation.

Pickle: For model serialization.

Colab: For executing the notebook in a cloud-based environment.

Results
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The final Random Forest model achieved high accuracy in detecting fraudulent transactions, making it a reliable tool for identifying potential credit card fraud.

