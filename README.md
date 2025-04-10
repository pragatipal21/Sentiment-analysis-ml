# Sentiment Analysis of Amazon Product Reviews 🛍️🧠

This project uses Machine Learning and Natural Language Processing (NLP) to classify product reviews from Amazon as **positive**, **neutral**, or **negative**.

## 💡 Project Highlights
- Dataset: Amazon Product Review CSV
- Preprocessing: Text cleaning, TF-IDF
- ML Algorithm: Logistic Regression
- Evaluation: Accuracy, Confusion Matrix, Classification Report
- Deployment Ready: Model + TF-IDF saved using `joblib`

---

## 📊 Tech Stack
- Python 🐍
- Pandas, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- [Optional] Streamlit for Web Interface

---

## 🔍 How it Works
1. **Data Preprocessing**
   - Reads CSV and assigns sentiment labels (positive, neutral, negative)
2. **Visualization**
   - Countplots and boxplots to analyze sentiment distribution
3. **Model Training**
   - TF-IDF used for feature extraction
   - Logistic Regression with class_weight balancing
4. **Evaluation**
   - Accuracy, Precision, Recall, F1
5. **Deployment**
   - Save model + vectorizer for later prediction

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/sentiment-analysis-ml.git
cd sentiment-analysis-ml
pip install -r requirements.txt
