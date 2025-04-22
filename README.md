# 📰 News Summary and Sentiment Analysis

This project combines **text summarization** and **sentiment analysis** techniques to analyze financial and general news articles. It demonstrates the use of NLP pipelines to extract meaningful summaries and evaluate sentiment, helping readers digest large volumes of information quickly and assess tone or market sentiment.

---

## 📦 Datasets Used

### 1. [CNN / DailyMail Dataset](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news)
- **Purpose**: Text summarization
- **Size**: 300,000+ news articles
- **Fields**: `id`, `article`, `highlights`
- **Task**: Abstractive and extractive summarization
- **Metric**: ROUGE score

### 2. [BBC News Summary](https://www.kaggle.com/datasets/pariza/bbc-news-summary)
- **Purpose**: Additional training and testing for summarization
- **Categories**: Business, Politics, Sports, Tech, Entertainment

### 3. [FinancialPhraseBank](https://www.researchgate.net/publication/251231364)
- **Purpose**: Sentiment analysis for financial texts
- **Labels**: Positive, Negative, Neutral

---

## 🧠 Project Pipeline

### 📜 Text Summarization
- Used Transformer-based models like **BART** and **T5**.
- Evaluated summaries using **ROUGE** metrics.
- Applied on CNN/DailyMail and BBC datasets.

### 📈 Sentiment Analysis
- Trained classification models using the **FinancialPhraseBank**.
- Used traditional ML (Logistic Regression, SVM) and transformer-based methods (BERT).
- Evaluated using accuracy, F1 score.

---

## 💡 Applications

- **Financial News Analysis**: Quickly extract key points and tone from market-related news.
- **Media Monitoring**: Use as a backend for alert systems or news aggregation platforms.
- **Investor Tools**: Enhance dashboards with contextual summaries and sentiment scores.

---

## 🛠️ Tech Stack

- Python
- Hugging Face Transformers
- Scikit-learn
- NLTK / SpaCy
- Pandas / NumPy
- Jupyter Notebook

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/news-summary-sentiment.git
   cd news-summary-sentiment
