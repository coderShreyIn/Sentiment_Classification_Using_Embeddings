## 🧠 Sentiment Classification Using Sentence Transformers

~ This project implements an embedding-based sentiment classification system that classifies Twitter tweets into Positive, Negative, or Neutral sentiments using Sentence Transformer embeddings and a machine learning classifier.

~ Unlike API-based solutions, this system works fully offline, making it efficient, scalable, and reproducible.

## 📌 Problem Statement

~ Social media platforms generate millions of posts daily, making manual sentiment analysis impractical. Understanding public sentiment helps brands, governments, and organizations make informed decisions.

## 🎯 Objective

~ The goal of this project is to build a sentiment classifier using:

1. Text preprocessing and cleaning

2. Transformer-based semantic embeddings

3. A machine learning classification model

## 📊 Dataset

~ Dataset: Twitter Tweets Sentiment Dataset
~ Size: ~27,000 tweets
~ Columns:

    - textID
    
    - text
    
    - selected_text
    
    - sentiment

~ Sentiment Labels:

     - Positive
      
     - Negative
      
     - Neutral

## 🔗 Dataset Link:
https://www.kaggle.com/datasets/yasserh/twitter-tweets-sentiment-dataset

## 🛠️ Technologies Used

1. Python
2. Pandas, NumPy
3. NLTK (text preprocessing)
4. Sentence Transformers (all-MiniLM-L6-v2)
5. Scikit-learn (Logistic Regression)
6. Matplotlib, Seaborn
7. WordCloud
8. VS Code (Jupyter Notebook)

## 🧠 Embedding Model Used

~ We use the lightweight transformer model:
> all-MiniLM-L6-v2

~ Key Features:
> 384-dimensional semantic embeddings

~ Captures contextual meaning of sentences
> Fast and lightweight

~ Works completely offline

~ No API dependency

## 🔄 Project Workflow

1. Exploratory Data Analysis (EDA)

2. Text preprocessing and cleaning

3. Word cloud visualization

4. Embedding generation using Sentence Transformers

5. Train-test split

6. Model training using Logistic Regression

7. Model evaluation using classification metrics

8. Custom tweet sentiment prediction

## 📈 Results

~ The model successfully classifies tweets into positive, negative, and neutral categories.

~ Transformer-based embeddings capture contextual meaning effectively.

~ The classifier performs strongly on short social media texts.

~ Custom user-defined tweets were accurately classified.

## 🧪 Sample Predictions
"I absolutely love this new phone!" 
→ Positive

"This service is horrible and frustrating"
→ Negative

"The event happened yesterday"
→ Neutral

## 🚀 How to Run the Project

1️⃣ Clone the repository
git clone https://github.com/coderShreyIn/Sentiment_Classification_Using_Embeddings.git
cd Sentiment_Classification_Using_Embeddings
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook

Open in VS Code or Jupyter:
> jupyter notebook

Run all cells sequentially.

## 📦 No API Key Required

This project uses offline Sentence Transformers, so:

❌ No Gemini API key needed

❌ No rate limits

❌ No internet dependency after first model download

## 📊 Model Performance

- Logistic Regression trained on transformer embeddings

- High accuracy on multi-class sentiment classification

- Good generalization on unseen tweets

## ⚠️ Limitations

- Sarcasm detection is challenging

- Very short texts may reduce classification confidence

- Mixed sentiment sentences can cause ambiguity

## 🔮 Future Improvements

- Fine-tune a transformer model directly for sentiment classification

- Add confidence score display

- Implement hyperparameter tuning

- Deploy as a web app (Streamlit/Flask)

- Add real-time tweet streaming analysis

## 🌍 Real-World Applications

- Social media sentiment monitoring
- Brand reputation analysis
- Customer feedback analytics
- Political opinion mining
- Product review classification
- Chatbot emotion detection

## 👨‍💻 Author

~ Shrey Dak
  > AI & Machine Learning Enthusiast
  > GitHub: https://github.com/coderShreyIn

## ⭐ If You Found This Useful

~ Please consider giving this repository a ⭐ on GitHub!
