# Sentiment Classification Using Embeddings

This project implements an **embedding-based sentiment classification system** that classifies Twitter tweets into **Positive**, **Negative**, or **Neutral** sentiments using **Gemini text embeddings** and machine learning.

---

## 📌 Problem Statement
Social media platforms generate millions of posts daily, making manual sentiment analysis impractical. Understanding public sentiment helps brands, governments, and organizations make informed decisions.

---

## 🎯 Objective
The goal of this project is to build a sentiment classifier using:
- Text preprocessing and cleaning
- Semantic embeddings generated using Gemini
- A machine learning classification model

---

## 📊 Dataset
- **Dataset:** Twitter Tweets Sentiment Dataset  
- **Size:** ~27,000 tweets  
- **Columns:** `textID`, `text`, `selected_text`, `sentiment`  
- **Sentiment Labels:** Positive, Negative, Neutral  

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- NLTK (text preprocessing)
- Google Gemini Embeddings (`text-embedding-004`)
- Scikit-learn (Logistic Regression)
- Matplotlib, Seaborn
- WordCloud
- VS Code (Jupyter Notebook)

---

## 🔄 Project Workflow
1. Exploratory Data Analysis (EDA)
2. Text preprocessing and cleaning
3. Word cloud visualization
4. Embedding generation using Gemini
5. Model training using Logistic Regression
6. Model evaluation using classification metrics
7. Custom tweet sentiment prediction

---

## 📈 Results
- The model successfully classifies tweets into positive, negative, and neutral categories.
- Semantic embeddings capture contextual meaning effectively.
- Custom user-defined tweets were accurately classified.

---

## 🧪 Sample Predictions
-"I absolutely love this new phone!" → Positive
-"This service is horrible and frustrating" → Negative
-"The event happened yesterday" → Neutral

---

## 🚀 How to Run the Project

1. Clone the repository:
- git clone https://github.com/coderShreyIn/Sentiment_Classification_Using_Embeddings.git

2. Install required dependencies:
- pip install -r requirements.txt

3. Add your Gemini API key in the code:
- api_key = "WRITE_YOUR_API_KEY_HERE"

4. Open and run the notebook in VS Code or Jupyter Notebook.
