# 🧠 Sentiment Analysis on Tourism Reviews

This project aims to analyze customer sentiments from Agoda and Traveloka reviews using natural language processing (NLP) techniques.

## 📁 Dataset
- Collected from review platforms Agoda & Traveloka
- Includes customer review text, ratings, and metadata
- Collected using Chrome WebDriver for automated web scraping of hotel reviews

## 🔧 Tools & Libraries
- Python, Jupyter Notebook, Google Colab
- NLTK, scikit-learn, pandas
- Custom emoji and teencode dictionary

## 🧪 Preprocessing
- Conducted exploratory data analysis (EDA) to identify missing values, remove duplicates, and visualize data distribution
- Tokenization, stopwords removal (with custom Vietnamese list)
- Teencode & emoji normalization
- Applied TF-IDF vectorization to transform Vietnamese reviews into numerical feature vectors for sentiment classification

## 🧠 Modeling
- Used Logistic Regression and SVM for sentiment classification
- Evaluated via accuracy, precision, recall

## 📂 Files
- `Final_NLP.ipynb`: Main notebook for training & evaluation
- `Data_NLP.ipynb`: Data cleaning and preprocessing
- `teencode.txt`, `emojicon.txt`: Custom normalization files
- `vietnamese-stopwords-1.txt`: Vietnamese stopword list
