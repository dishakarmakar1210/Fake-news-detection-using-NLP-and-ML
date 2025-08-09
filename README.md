

# Fake News Detection 📰

## 📌 Project Overview

This project implements a **Fake News Detection system** using Natural Language Processing (NLP) and Machine Learning techniques.
The goal is to classify news articles as *real* or *fake* based on their content.

## 🚀 Features

* Data preprocessing (tokenization, stopword removal, lemmatization)
* Text feature extraction using **TF-IDF Vectorization**
* Multiple ML models tested:

  * Logistic Regression
  * Decision Tree Classifier
  * Random Forest Classifier
  * Gradient Boosting Classifier
* Model evaluation with **accuracy, classification report, and confusion matrix**

## 📂 Dataset

The dataset is **not included** in this repository due to its large size.
You can download it from:

```
https://www.kaggle.com/code/maxcohen31/nlp-fake-news-detection-for-beginners/input
```

After downloading, place it in the project folder and update the notebook path accordingly.

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## 📖 Usage

Run the Jupyter Notebook:

```bash
jupyter notebook fake_news_detection.ipynb
```

Follow the steps in the notebook to preprocess the data, train models, and evaluate results.

## 📊 Results

* Best performing model: **Random Forest**
* Accuracy achieved: **99.83%**

## 📌 Requirements

See `requirements.txt` for all dependencies:

```
numpy
pandas
matplotlib
seaborn
scikit-learn
nltk
```




