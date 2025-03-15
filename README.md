# Sentiment Analysis on Amazon Reviews

This project performs **sentiment analysis** on Amazon product reviews using **machine learning techniques**. The goal is to classify reviews as **positive** or **negative** based on text data.

## 📌 Dataset Overview
- Contains Amazon product reviews with columns like **ratings, feedback, review text, variations, and date**.
- **Binary sentiment classification:**  
  - **Positive Sentiment:** Ratings of **3, 4, or 5**  
  - **Negative Sentiment:** Ratings of **1 or 2**  
- Skipping neutral ratings (3) to avoid data skew.

## 🏗️ Approach
1. **Data Preprocessing**
   - Text cleaning (removing stopwords, punctuation, etc.)
   - Handling missing values
   - Feature engineering (e.g., review length, feedback analysis)

2. **Model Training**
   A) MODEL 1: RANDOM FOREST
   B) MODEL 2: XGBOOST
   C) MODEL 3: DESCISION TREE CLASSIFIER

4. **Performance Metrics**
   -  MODEL 1: RANDOM FOREST: **Accuracy:** 93.6%
   -  MODEL 2: XGBOOST: **Accuracy:** 
   -  MODEL 3: DESCISION TREE CLASSIFIER: **Accuracy:** 
   - **Precision:** 94.5%
   - **Recall:** 98.9%
   - **F1 Score:** 96.7%

## 🚀 How to Run
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/sentiment-analysis-amazon.git
cd sentiment-analysis-amazon
