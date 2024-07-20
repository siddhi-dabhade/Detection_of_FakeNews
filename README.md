# Detection_of_FakeNews

# Overview
Welcome to the Detection of Fake News project! This repository houses the code and resources for identifying fake news articles using machine learning techniques. Our objective is to build a robust and efficient system that can distinguish between real and fake news based on textual content.

# Features
1. Feature Extraction:
   Use techniques such as TF-IDF and word embeddings to convert text into numerical features.
2. Model Training:
   Implement and train various machine learning models, including logistic regression, Naive Bayes, SVM, and deep learning models.
3. Model Evaluation:
   Evaluate models using metrics such as accuracy, precision, recall, and F1-score.

# Model:
To build the model, we make use of:
1. TfidfVectorizer-
   The TfidfVectorizer is a tool in natural language processing (NLP) that transforms text data into numerical feature vectors. It combines two methods:
       Term Frequency (TF): Measures how frequently a term appears in a document.
       Inverse Document Frequency (IDF): Measures how important a term is by reducing the weight of terms that appear frequently across all documents.
  The product of TF and IDF gives the TF-IDF score, which reflects the importance of a term in a document relative to the entire corpus. This helps in highlighting important words and reducing the influence of common but less informative words.

2. PassiveAggressiveClassifier-
   The PassiveAggressiveClassifier is a type of machine learning model used for binary classification tasks. It remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting.

# Requirements
We make use of various python bulit-in libraries like-
1. Pandas
2. NumPy
3. Scikit-learn
