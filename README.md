# 📄 Resume Scanner

This project is an **AI-powered Resume Scanner** that uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify resumes into different job categories.  
It also provides **visual insights** such as word clouds, frequency distribution, and category distribution plots.

---

## 🚀 Features
- ✅ Resume text cleaning & preprocessing  
- ✅ TF-IDF Vectorization for feature extraction  
- ✅ Multi-class classification using **K-Nearest Neighbors (KNN)** with One-vs-Rest strategy  
- ✅ Visualization of resume categories with **Barplots & Pie charts**  
- ✅ **Word Clouds** and **Frequency Distribution** of keywords  
- ✅ Lemmatization & Stopword removal for better text processing  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Libraries:**  
  - `numpy`, `pandas` → Data handling  
  - `matplotlib`, `seaborn` → Data visualization  
  - `scikit-learn` → Machine Learning models  
  - `nltk` → Text preprocessing (stopwords, lemmatization, tokenization)  
  - `wordcloud` → Word cloud generation  

---

## 📊 Workflow
1. Load and preprocess resumes from dataset (`UpdatedResumeDataSet.csv`).  
2. Clean text (remove URLs, mentions, hashtags, special chars, etc.).  
3. Tokenize and remove stopwords.  
4. Apply **Lemmatization** to normalize words.  
5. Convert text into features using **TF-IDF**.  
6. Train & evaluate a **One-vs-Rest KNN classifier**.  
7. Visualize results (bar chart, pie chart, word cloud, frequency distribution).  

---

## 📈 Model Performance
- Training Accuracy: ~**XX%**  
- Validation Accuracy: ~**YY%**  

*(Exact accuracy depends on dataset & split.)*

---

## 📷 Sample Outputs
### 📊 Category Distribution
Bar chart and pie chart showing distribution of job categories.  

### ☁ Word Clouds
- **100 words** word cloud  
- **200 words** word cloud  

### 🔡 Frequency Distribution
Most frequent words across all resumes.  

---

 
