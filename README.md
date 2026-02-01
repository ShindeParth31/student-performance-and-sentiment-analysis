This repository contains two end-to-end Machine Learning tasks implemented using **Python**, **Pandas**, **Scikit-learn**, and **Natural Language Processing (NLP)** techniques. The project is suitable for academic submission, mini-projects, and practical ML learning.

Task 1: Student Pass/Fail Prediction

Objective

Predict whether a student will **Pass or Fail** based on their **Study Hours** and **Attendance Percentage** using a **Logistic Regression** classification model.

Dataset

File: `student_pass_fail.csv`

Columns:

* `Study_Hours` – Number of hours a student studies per week
* `Attendance` – Attendance percentage
* `Pass` – Target variable (1 = Pass, 0 = Fail)

Steps Performed

1. Dataset loading and inspection
2. Data exploration and visualization
3. Feature selection
4. Train-test split
5. Logistic Regression model training
6. Model evaluation using:
  * Accuracy
  * Confusion Matrix
7. Insights on key predictors

Evaluation Metrics
* Accuracy Score
* Confusion Matrix (TP, TN, FP, FN)
  

Task 2: Sentiment Analysis using NLP

Objective
Analyze customer reviews and classify them as **Positive** or **Negative** using **Natural Language Processing** and **Logistic Regression**.

Dataset

File: `reviews_sentiment.csv`

Columns:

* `Review` – Customer review text
* `Sentiment` – Sentiment label (`positive` or `negative`)

Text Preprocessing
* Convert text to lowercase
* Remove punctuation and special characters
* Remove stopwords
* Tokenization and lemmatization

Feature Engineering
* Text vectorization using **TF-IDF (Term Frequency–Inverse Document Frequency)**

Model Used
* Logistic Regression Classifier

Evaluation Metrics
* Accuracy
* Precision
* Recall
* F1-Score

 Insights
* Common words influencing positive sentiment (e.g., *excellent, amazing*)
* Common words influencing negative sentiment (e.g., *poor, worst*)


 Technologies Used
* Python 3
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* NLTK
* Jupyter Notebook / Google Colab

Conclusion

This project demonstrates the practical application of **classification algorithms** and **NLP techniques** to solve real-world problems. It provides hands-on experience with data preprocessing, model building, evaluation, and result interpretation.



