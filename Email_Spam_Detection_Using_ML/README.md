📧 Email Spam Detection using Machine Learning

📌 Project Overview

Spam emails are unwanted messages that often contain advertisements, scams, or phishing attempts. Detecting such emails is essential to protect users and improve communication efficiency.

This project builds a machine learning model using Python to classify emails as Spam or Not Spam (Ham) based on their content.

🎯 Objective

To preprocess email text data

To extract meaningful features using NLP techniques

To train a machine learning model for spam classification

To evaluate model performance using appropriate metrics

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Natural Language Processing (TF-IDF)

📂 Dataset

The dataset contains labeled email messages:

Spam (1) → Unwanted / promotional emails

Ham (0) → Legitimate emails

⚙️ Workflow

Data Collection

Loaded dataset using Pandas

Data Preprocessing

Removed special characters

Converted text to lowercase

Cleaned and prepared text data

Feature Extraction

Used TF-IDF Vectorizer to convert text into numerical form

Model Training

Applied Multinomial Naive Bayes algorithm

Model Evaluation

Accuracy Score

Confusion Matrix

Classification Report

Model Saving

Saved trained model and vectorizer using pickle

Prediction

Built a function to classify new email messages

📊 Results

Achieved high accuracy in classifying spam and non-spam emails

Model performs well in identifying common spam patterns

Evaluation metrics used:

Accuracy

Precision

Recall

F1-score

🔍 Key Insights

Spam datasets often show class imbalance

Words like “free”, “win”, “urgent” strongly indicate spam

Recall is more important than accuracy in spam detection

Model performance depends heavily on text preprocessing and feature extraction

The model may struggle with sophisticated or context-based spam

⚠️ Limitations

Cannot fully detect advanced phishing emails

Depends on training data patterns

Ignores deep contextual meaning of text

🚀 Future Improvements

Try advanced models like Logistic Regression or SVM

Use Deep Learning (LSTM / NLP models)

Deploy as a web application using Streamlit

Improve preprocessing for better accuracy

▶️ How to Run the Project

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

Run the Python file:

python spam_detection.py

Test prediction:

predict_spam("Congratulations! You won a free prize")

💾 Model Files

spam_model.pkl → Trained model

vectorizer.pkl → TF-IDF vectorizer

👩‍💻 Author

Navya Sunil K S
BCA Student | Aspiring Data Scientist
