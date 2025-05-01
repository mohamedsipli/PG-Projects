# News Article Classification using NLP

This project involves building an NLP-based text classification model to categorize news articles into 20 distinct topics, demonstrating expertise in machine learning and natural language processing.

## Project Description

The objective was to create a system that can automatically determine the subject category of a given news article. This required implementing a complete NLP pipeline from raw text to a trained classifier, including detailed data analysis, text preprocessing, and feature engineering suitable for text data.

## Domain

Text Analysis / Natural Language Processing (NLP) / Multi-class Classification

## Key Techniques & Skills Demonstrated

* **Natural Language Processing (NLP):**
    * Text Preprocessing: Lowercasing, removing punctuation and numbers, Tokenization, Stop Word Removal (using NLTK), Stemming (using Porter Stemmer).
* **Feature Extraction:**
    * TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
    * Using N-grams (Unigrams and Bigrams) to capture more context and create a rich feature representation.
* **Machine Learning Classification:**
    * Multi-class Classification task.
    * Training a Linear Support Vector Machine (SVM) model, known for its effectiveness on high-dimensional sparse data like TF-IDF features.
* **Data Analysis & Visualization:** Explored dataset distribution and characteristics, analyzed most common words before and after preprocessing. Visualized results with Confusion Matrix.
* **Model Evaluation:** Assessed model performance using:
    * Accuracy Score
    * Classification Report (Precision, Recall, F1-score per class)
    * Confusion Matrix.
* **Model Interpretation:** Analyzed the most influential features (words/n-grams) per category based on model coefficients.
* **Libraries:** `scikit-learn`, `nltk`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `re`.

## Dataset

20 Newsgroups Dataset - a widely-used collection of approximately 18,000 newsgroup documents, partitioned across 20 different topics. (Dataset is loaded directly via `sklearn.datasets`).

## Outcome

Successfully implemented an end-to-end text classification system, achieving solid performance on a challenging multi-class text dataset and demonstrating proficiency in key NLP and machine learning techniques.

## Project Context

This project was completed as coursework for the **Data Mining (CAS764)** course during the **Master of Science (M.Sc.) in Computer Science** program at the **Department of Computer Applications, National Institute of Technology, Tiruchirappalli** in **Spring 2016**, under the guidance of **Prof. Ramadoss**.
