# Spam Message Classification Project (Python + Machine Learning)

This project is a simple implementation of spam detection using machine learning.
The main goal of the project is to classify text messages into two categories:
*Spam* or *Ham (Not Spam)*.  
I created this project to understand the basic workflow of text preprocessing,
feature extraction, and model building using Python.

# Project Aim
The aim of this project is:
1 To learn how to work with text data in Python
2 To understand how TF-IDF converts text into numbers
3 To build a simple machine learning model
4 To test and evaluate a model’s performance
5 To apply ML in real-world problems like spam filtering

# Files in This Project
1 *spam_classifier.py* → Main Python code  
2 *spam_data.csv* → Dataset (optional)  
3 *README.md* → Project documentation  
4 *STATEMENT.txt* → Declaration file  
5 *spam_nb_model.joblib* → Saved ML model  
6 *tfidf_vectorizer.joblib* → Saved TF-IDF vectorizer  

Reference image used in project:  
/mnt/data/0d86aa56-7afd-467f-a4b0-1fb9f2d8e4c8.png

# Technologies Used
1 Python  
2 Pandas  
3 Scikit-learn  
4 TF-IDF Vectorizer  
5 Naive Bayes Classifier  
6 VS Code  

These tools helped in handling data, converting text into vectors, training the model,
and evaluating results.

# How the Project Works

# 1. Loading Data
The script first tries to load spam_data.csv.  
If the file doesn't exist, it creates a small sample dataset.

# 2. Preprocessing
1 Removes missing values  
5 Converts labels (“ham”, “spam”) into numbers (0, 1)  
3 Splits dataset into training & testing sets  
4 Applies TF-IDF to convert text into numeric features  

# 3. Model Training
A *Multinomial Naive Bayes* classifier is used.  
It is simple, fast, and commonly used for text classification.

# 4. Model Evaluation
The program prints:
1 Accuracy  
2 Precision, Recall, F1-Score  
3 Confusion Matrix  

# 5. Making Predictions
The script includes a predict_one() function which tells whether a new message is spam or ham.


# How to Run the Project

# Step 1: Install dependencies
#Step 2: Run the script
# Step 3 (Optional): Add your own dataset
Create a file named spam_data.csv with the format:
\
