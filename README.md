## 📰 Fake News Prediction using Machine Learning
This project builds a machine learning model to classify news articles as fake or real. It leverages natural language processing (NLP) techniques for text cleaning, feature extraction, and uses several classifiers to detect misinformation;

## 🚀 Project Overview
- Goal: Automatically classify news articles as fake or real.

Approach:
1. Text preprocessing (stopword removal, lemmatization)
2. Feature engineering using TF-IDF
3. Model training with classifiers like Logistic Regression, PassiveAggressiveClassifier, etc.
- Dataset: News data labeled as fake or real (loaded from CSV).
📁 Project Structure
```
📦 Fake-News-Prediction/
├── Fake News Prediction.ipynb   
├── README.md                    
├── requirements.txt           
└── data/
    └── fake_or_real_news.csv  
```
## 📊 Dataset
- Columns:
1. title: The title of the article
2. text: Full article text
3. label: Real or Fake

Ensure the dataset is available in a data/ directory with the name fake_or_real_news.csv.

## 🧠 Models Used
TF-IDF Vectorizer: For transforming text into numerical features.
- Classifiers:
    - Logistic Regression
    - PassiveAggressiveClassifier

## 🛠️ Installation & Usage
Clone the repo
```
git clone https://github.com/ibukunoluwa792/fake_news.git
cd fake_news
```
## 📈 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision/Recall/F1-score
- ROC-AUC Curve

## 📌 Results Snapshot
Model	Accuracy
Logistic Regression	~96%

## 📝 License
This project is open-source under the MIT License.
