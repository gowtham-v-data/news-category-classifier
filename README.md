# 📰 News Category Classifier

🚀 A Machine Learning project that classifies news headlines into categories like **Sports, Politics, Technology, and Business** using Natural Language Processing (NLP).

---

## 📌 Project Overview
This project demonstrates an end-to-end NLP pipeline:
- Text preprocessing
- Feature extraction
- Model training
- Prediction

The model analyzes news headlines and predicts their category automatically.

---

## 🧠 Features
✔️ Text preprocessing (Tokenization, Stopword Removal, Stemming)  
✔️ TF-IDF vectorization  
✔️ Classification using Naive Bayes  
✔️ Handling imbalanced dataset using sampling  
✔️ Real-time prediction function  

---

## 🛠️ Tech Stack
- Python 🐍  
- NLTK  
- Scikit-learn  
- Pandas  
- Jupyter Notebook  

---

## 📊 Dataset
- Source: Kaggle News Category Dataset  
- Format: JSON  
- Categories used:
  - SPORTS  
  - POLITICS  
  - BUSINESS  
  - TECH  

---

## ⚙️ Workflow
1. Load dataset  
2. Clean and preprocess text  
3. Tokenization & Stopword removal  
4. Stemming using Porter Stemmer  
5. Convert text → TF-IDF vectors  
6. Train model (Naive Bayes)  
7. Evaluate accuracy  
8. Predict new inputs  

---

## 📈 Model Performance
- Accuracy: **~91%**  
- Improved results after handling class imbalance  

---

## 🔍 Example Prediction
```python
predict_news("India wins cricket world cup")
# Output: SPORTS
