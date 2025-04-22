# 📚 Text Analytics Projects: Summarization & Sentiment Analysis

This repository contains two datasets used for Natural Language Processing (NLP) tasks — extractive summarization of BBC News articles and sentiment analysis of financial news headlines. These datasets are ideal for experimentation in text processing, summarization, sentiment classification, and building end-to-end NLP applications.

---

## 📌 Datasets Included

### 1. **BBC News Summary**  
**Task:** Extractive Text Summarization  
**Source:** [UCD Machine Learning Group](http://mlg.ucd.ie/datasets/bbc.html)  
**License:** CC0: Public Domain

#### 📖 Description
The dataset contains **417 political news articles** from the BBC (2004–2005). Each article is paired with **5 extractive summaries**, making this dataset suitable for exploring classical summarization techniques that select and score sentences.

#### 📂 Structure
- `News Articles/`: Contains full-length political news articles.
- `Summaries/`: Contains 5 extractive summaries per article.
- The title of each article is embedded in the first clause of the article text.

#### 📌 Use Cases
- Train unsupervised extractive summarizers
- Evaluate sentence scoring algorithms
- Explore content reduction methods in news media

---

### 2. **Sentiment Analysis for Financial News**  
**Task:** Sentiment Classification  
**Source:** FinancialPhraseBank (Malo et al., 2014)  
**License:** CC BY-NC-SA 4.0

#### 📖 Description
This dataset includes **4,837 financial news headlines** annotated with sentiment labels from a retail investor’s perspective. Each headline is labeled as **positive**, **neutral**, or **negative**.

#### 📂 Structure
- `all-data.csv`: Two columns — `Sentiment` and `News Headline`

#### 📌 Use Cases
- Train sentiment classifiers for financial applications
- Build financial news filtering or summarization engines
- Experiment with transfer learning using BERT/FinBERT

---
