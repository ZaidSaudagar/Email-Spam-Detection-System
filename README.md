# 📧 **Email Spam Detection System**

@ZaidSaudagar 


*A Machine Learning--Based Approach for Identifying Spam Emails*

## 📌 Overview

Spam emails continue to be one of the largest digital
nuisances---ranging from promotional clutter to malicious phishing
attempts. This project focuses on developing a machine learning model
that automatically classifies emails as spam or ham (legitimate) using
text-based features.

## 🎯 Project Goals

-   Build an accurate, automated spam classification system
-   Reduce false negatives and improve email security
-   Analyze keyword patterns in spam messages
-   Compare multiple ML algorithms to find the best performer
-   Provide a clear, reproducible workflow

## 📂 Dataset Details

-   Labeled email dataset with spam and ham messages
-   Spam: 13.41% \| Ham: 86.59%
-   Preprocessing: cleaning, tokenization, stopword removal, TF-IDF
    vectorization

## 🔍 Exploratory Data Analysis (EDA)

Common spam keywords identified: **"free", "call", "txt", "text",
"now"**

Spam emails generally contain short, direct, urgent-language phrases.

## 🧠 Machine Learning Models Used

-   Multinomial Naive Bayes (Best Performer)
-   SVM
-   Decision Tree
-   Logistic Regression

## 📊 Model Performance

Multinomial Naive Bayes achieved: - **Recall:** 98.49% - **High accuracy
& F1-score** - Fast and efficient for text-based classification

## 🛠️ Technologies Used

-   Python\
-   Pandas, NumPy\
-   Scikit-learn\
-   Matplotlib, Seaborn\
-   NLTK / Regex\
-   Jupyter Notebook

## 📐 Workflow

1.  Import & inspect dataset\
2.  Preprocess and clean data\
3.  Perform EDA\
4.  Vectorize text using TF-IDF\
5.  Model training\
6.  Evaluation & comparison\
7.  Final model selection\
8.  Insights & conclusion

## 🏁 Results & Conclusion

The project demonstrates that ML can effectively filter spam by
analyzing email text patterns. With strong recall and accuracy, Naive
Bayes proved highly suitable for this task. Future enhancements include
deep learning approaches, deployment APIs, and real‑time filtering.

## 🚀 Future Enhancements

-   Add LSTM/BERT models\
-   Real‑time email classification API\
-   GUI or web interface\
-   Model deployment with pickle


## 🤝 Contribution

Fork the repo, open issues, and submit PRs to improve the system.

## ⭐ Show Your Support

Star ⭐ the repository if you find it helpful!
