# 📧 Spam Email Classifier using Naive Bayes

## 📌 Project Overview

This project builds a machine learning model to classify messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

The project includes data preprocessing, visualization, feature extraction, and comparison of multiple Naive Bayes models.

---

## 🧠 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* NLTK

---

## 📊 Dataset

SMS Spam Collection Dataset

* Contains ~5572 messages
* Labels: Spam / Ham

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Removed unnecessary columns (`Unnamed`)
* Renamed columns to `Category` and `Text`
* Converted labels:

  * Spam → 1
  * Ham → 0

---

### 2. Exploratory Data Analysis (EDA)

* Spam vs Ham distribution (donut chart + count plot)
* Message length analysis
* Histogram of text length
* Comparison of length distribution for spam and ham

---

### 3. Feature Extraction

* Used **CountVectorizer** to convert text into numerical features

---

### 4. Train-Test Split

* 70% Training
* 30% Testing

---

### 5. Models Used

#### 🔹 Multinomial Naive Bayes

* Suitable for text classification
* Works on word frequency

#### 🔹 Bernoulli Naive Bayes

* Works on binary features (word presence)

---

### 6. Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1 Score

---

### 7. Visualization

* Confusion Matrix for both models
* Heatmap comparison of metrics

---

## 📈 Results

* Both models perform well on spam detection
* Multinomial Naive Bayes gives strong performance for text data

---

## 🧪 Example Output

* Input: "Free entry in a competition"
* Output: Spam

---

## 🚀 How to Run

1. Open notebook in Google Colab
2. Upload dataset (`spam.csv`) or connect Google Drive
3. Run all cells
4. View predictions and evaluation metrics

---

## 💡 Key Learnings

* Text preprocessing and cleaning
* Feature extraction using CountVectorizer
* Comparison of ML models
* Evaluation using multiple metrics
* Data visualization techniques

---

## 📌 Author

* Anandhan A
