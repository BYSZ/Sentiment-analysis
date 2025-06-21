# Sentiment-analysis
 Capturing the emotions in the text can help companies quickly mine meaningful key  information from massive texts, better understand the voice of users, and accurately extract  the hidden views of the text, which can guide product development, further improve functions,  and analyze market trends wait.  
 
 
## 📌 Project Summary
This project demonstrates a comparison between traditional machine learning models and deep learning approaches for sentiment classification. The goal is to classify tweets as positive or negative using three machine learning models: Naive Bayes, K-Nearest Neighbors (KNN), and Convolutional Neural Network (CNN). It uses a cleaned version of the Sentiment140 dataset with 300,000 tweets, focusing on analyzing performance through accuracy, precision, recall, and execution time.

## 🔍 Models Implemented
Naive Bayes Classifier (MultinomialNB)

- Text vectorization via CountVectorizer

- Hyperparameter tuning via GridSearchCV

- Fastest and most accurate in our experiments

K-Nearest Neighbors (KNN)

- Dimensionality reduction using TruncatedSVD

- Slower but interpretable and simple to implement

Convolutional Neural Network (CNN)

- Implemented using TensorFlow/Keras

- Tokenization and padding for deep learning input

- Higher complexity, slower, but decent accuracy

## 📊 Experimental Results
| Model                | Accuracy | Precision | Recall | Execution Time |
|----------------------|----------|-----------|--------|----------------|
| Naive Bayes          | 0.7612   | 0.7626    | 0.7612 | 2.93 s         |
| K-Nearest Neighbors  | 0.6675   | 0.6675    | 0.6675 | 117.78 s       |
| CNN                  | 0.7259   | 0.6974    | 0.7259 | 2146.79 s      |

## 📂 Dataset
This project is based on a subset of the Sentiment140 dataset, originally created by Go, Bhayani, and Huang (2009) for sentiment classification research. The full dataset contains 1.6 million tweets collected via the Twitter API, each labeled for sentiment (0 = negative, 4 = positive). Each record includes the following fields:

- target (sentiment label)

- ids (tweet ID)

- date (date of the tweet)

- flag (query used)

- user (username)

- text (tweet content)

Note: Due to university policy and privacy constraints, we are unable to redistribute the specific subset of the dataset used in this assignment. However, our preprocessing and model implementation are compatible with any tweet-based sentiment dataset following the same structure.  

Reference:
Go, A., Bhayani, R., & Huang, L. (2009). Twitter sentiment classification using distant supervision. CS224N Project Report, Stanford, 1(2009), p.12.

## ⚠️ Academic Integrity Notice

This repository contains code written for educational purposes.  

Please **do not copy** or reuse this work for academic submission in any course, as this may violate university academic honesty policies.  
You are welcome to use it as reference for personal learning, but not for plagiarism.
