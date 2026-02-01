# CODETCH-Task-4
Perfect! Here’s your **FINAL copy–paste ready README.md** updated with your requested title exactly:

---

# Perform Sentiment Analysis on Textual Data (eg. Tweets, Reviews) Using Natural Language Processing (NLP) Techniques

**Intern Details:**
Name: Sahil Balkrushna Gadge
Company: CODETECH IT SOLUTIONS PVT. LTD
ID: CT12DR1813
Domain: Data Analytics
Duration: November 15th 2025 to February 15th 2026
Mentor: Neela Santhosh Kumar

---

**Project Overview:**
This project focuses on performing sentiment analysis on textual data such as user reviews or tweets using Natural Language Processing techniques. The objective is to demonstrate how raw text data can be cleaned, transformed into numerical features, and used to train a machine learning model for sentiment prediction. The model classifies text as either positive or negative sentiment.

---

**Objective:**
To build a sentiment analysis model that predicts the sentiment of textual data using NLP preprocessing and machine learning techniques.

---

**Dataset:**
The dataset is a manually created sample consisting of short user review sentences labeled with sentiment values.

**Sentiment Labels:**
1 → Positive
0 → Negative

---

**Tools and Technologies Used:**
Python 3
Jupyter Notebook
NumPy
Pandas
NLTK
Scikit-learn

---

**Steps Performed:**

**Data Preparation:**
Created a dataset containing positive and negative review sentences and converted it into a Pandas DataFrame.

**Text Preprocessing:**
Converted text to lowercase, removed special characters, removed stopwords using NLTK, and cleaned text for better feature extraction.

**Feature Extraction:**
Applied TF-IDF Vectorization using unigrams and bigrams with a limited feature set.

**Model Training:**
Implemented Logistic Regression, split the dataset into training and testing sets using a 75:25 ratio, and used stratified sampling.

**Model Evaluation:**
Evaluated the model using Accuracy Score, Confusion Matrix, and Classification Report including precision, recall, and F1-score.

---

**Results:**
The model achieved an accuracy of 25 percent on the test dataset. Due to the small dataset size, performance metrics are limited and not fully representative of real-world applications.

---

**Insights:**

* Text preprocessing significantly improves model input quality.
* TF-IDF effectively converts text into numerical features.
* Logistic Regression is suitable for binary sentiment classification.
* Small datasets can negatively impact accuracy and evaluation reliability.

---

**Files in Repository:**

* `task4.ipynb`: Jupyter Notebook containing sentiment analysis implementation and results
* `README.md`: Project documentation

---

**Conclusion:**
This project demonstrates a complete NLP-based sentiment analysis workflow including text cleaning, feature extraction, model training, and evaluation. The approach can be extended to larger datasets for real-world applications such as social media monitoring and customer feedback analysis.

---

