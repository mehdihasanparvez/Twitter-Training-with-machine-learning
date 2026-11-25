# Twitter Sentiment Analysis Using Machine Learning

## 📌 Project Overview
This project focuses on analyzing Twitter data and classifying tweets into four sentiment categories: **Positive, Negative, Neutral, and Irrelevant** using Machine Learning and Natural Language Processing (NLP) techniques.

The goal is to understand public opinions and identify sentiment patterns from social media text data.

## 📂 Dataset
The dataset contains Twitter posts with the following features:

- **ID:** Unique identifier for each tweet.
- **Entity:** Related topic or brand.
- **Sentiment:** Sentiment category.
- **Text:** Actual tweet content.

### Sample Data

| ID | Entity | Sentiment | Text |
|---|---|---|---|
| 2401 | Borderlands | Positive | I'm getting on Borderlands and I will murder you all. |

### Dataset Statistics

- Total records: 74,681
- Total features: 4
- Target variable: Sentiment
- Sentiment classes: 4

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Machine Learning

## 🔍 Project Workflow

1. Data Loading
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Text Cleaning
6. Feature Extraction using TF-IDF
7. Model Training
8. Model Evaluation

## 📊 Model Performance

The model was evaluated using Precision, Recall, F1-Score, and Accuracy.

| Sentiment | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Irrelevant | 0.91 | 0.84 | 0.87 |
| Negative | 0.90 | 0.91 | 0.91 |
| Neutral | 0.87 | 0.89 | 0.88 |
| Positive | 0.87 | 0.89 | 0.88 |

### Overall Performance

| Metric | Score |
|---|---:|
| Accuracy | **89%** |
| Macro Precision | 0.89 |
| Macro Recall | 0.88 |
| Macro F1-Score | 0.88 |
| Weighted F1-Score | 0.89 |

## 🎯 Results

The trained Machine Learning model achieved **89% accuracy** on the test dataset. It demonstrated good performance in classifying tweets into four sentiment categories.

## 🚀 Future Improvements

- Experiment with advanced ML algorithms.
- Implement deep learning models such as LSTM and BERT.
- Improve text preprocessing techniques.
- Develop a real-time Twitter sentiment analysis system.

## 👨‍💻 Author
Computer Science Student | Machine Learning Enthusiast

## ⭐ Conclusion
This project demonstrates how Machine Learning and NLP can be used to analyze social media text and automatically classify public opinions into different sentiment categories.
