# Spam Mail Detector

A Machine Learning and Natural Language Processing (NLP) project that classifies messages as Spam or Ham (Not Spam) using TF-IDF Vectorization and the Multinomial Naive Bayes algorithm.

---

## Project Overview

Spam messages are unwanted messages that often contain advertisements, scams, or fraudulent content. This project uses Machine Learning techniques to automatically identify and filter spam messages, helping improve communication security and user experience.

The model processes text messages, converts them into numerical features using TF-IDF, and classifies them using a Multinomial Naive Bayes classifier.

---

## Objectives

* Detect spam messages automatically.
* Classify messages as Spam or Ham.
* Apply Natural Language Processing techniques.
* Build and evaluate a Machine Learning model.
* Visualize and analyze text data.

---

## Dataset

The project uses the SMS Spam Collection Dataset containing labeled text messages.

### Categories

* Spam – Unwanted promotional or fraudulent messages.
* Ham – Legitimate and normal messages.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* WordCloud

---

## Workflow

1. Load Dataset
2. Data Exploration
3. Text Preprocessing
4. TF-IDF Feature Extraction
5. Train-Test Split
6. Model Training
7. Prediction
8. Performance Evaluation

---

## Machine Learning Model

### Multinomial Naive Bayes

Multinomial Naive Bayes is a supervised machine learning algorithm commonly used for text classification tasks. It calculates the probability of a message belonging to a specific class and classifies it as Spam or Ham based on the highest probability.

### Advantages

* Fast and efficient
* Suitable for text classification
* High accuracy
* Easy to implement

---

## Visualizations

### Spam vs Ham Distribution

![Spam Distribution](screenshots/spam_ham_distribution.png)

### Message Length Analysis

![Message Length](screenshots/message_length_histogram.png)

### Spam Word Cloud

![Spam Word Cloud](screenshots/spam_wordcloud.png)

### Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

---

## Results

The trained model successfully classified messages into Spam and Ham categories with high accuracy.

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Learning Outcomes

* Natural Language Processing (NLP)
* Text Preprocessing
* TF-IDF Feature Extraction
* Machine Learning Classification
* Data Visualization
* Model Evaluation

---

## Future Enhancements

* Support for Email Spam Detection
* Deep Learning-based Classification
* Real-Time Spam Filtering System
* Web Application Deployment

---

## Conclusion

The Spam Mail Detector project demonstrates the practical application of Machine Learning and Natural Language Processing in text classification. By using TF-IDF vectorization and the Multinomial Naive Bayes algorithm, the model effectively identifies spam messages and achieves strong classification performance.

---

## Author

Kousika Sabarisha

Artificial Intelligence & Machine Learning Internship Project
