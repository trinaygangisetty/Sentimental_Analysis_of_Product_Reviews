# 📊 Sentiment Analysis of Product Reviews  

## 🚀 Introduction  
This project performs **sentiment analysis** on **product reviews** to classify them as **positive, neutral, or negative** using **machine learning** and **natural language processing (NLP)**. The dataset contains **23,000+ reviews** from an e-commerce platform’s women’s clothing section, categorized by product type and rating.  

### **Objectives:**  
✔️ Extract **insights** from customer reviews.  
✔️ Classify sentiment using **ML models** (Logistic Regression, SVM, Naïve Bayes).  
✔️ Help businesses **understand customer satisfaction** trends.  
✔️ Identify **common themes** in positive and negative feedback.

---
## 📊 Dataset
The dataset consists of women’s clothing reviews with the following attributes:

- **Review Text** – The actual review left by a customer.
- **Rating** – A numerical score (1-5).
- **Sentiment Label** – Derived from rating (1-2 = Negative, 3 = Neutral, 4-5 = Positive).
- **Product Category** – Type of clothing item reviewed.
- **Age & Division** – Demographic information of reviewers.

## 🛠 Data Preprocessing Includes:
✔️ Handling missing values and cleaning text.  
✔️ Converting text into numerical features using Count Vectorizer.  
✔️ Splitting data into train-test sets (70-30).  

## 📈 Exploratory Data Analysis (EDA)
### Key insights from EDA:
✅ 82% of reviews are positive, indicating general customer satisfaction.  
✅ Older customers give more varied ratings, while younger ones are consistently positive.  
✅ "Fit" and "Comfort" are common words in positive reviews.  
✅ Negative reviews mention issues like "size", "return", "poor quality".  

### 🔍 Visualizations:
📌 **Sentiment Distribution:**
📌 **Word Cloud of Positive Reviews:**

---

## 🤖 Machine Learning Models
We trained the following classification models:

| Model                  | Accuracy | Precision | Recall |
|------------------------|----------|-----------|--------|
| Logistic Regression    | 95%      | 0.94      | 0.92   |
| Support Vector Machine | 93-94%   | 0.94      | 0.90   |
| Naïve Bayes            | ~85%     | 0.80      | 0.75   |

🏆 **Best Model:** Logistic Regression (95% Accuracy)

---

## 🚀 How to Use This Repository
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/trinaygangisetty/Sentimental_Analysis_of_Product_Reviews.git
cd Sentimental_Analysis_of_Product_Reviews
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
- Open Jupyter Notebook
- Run `notebooks/Sentiment_Analysis_ProductReviews.ipynb`
- View data analysis, preprocessing, and model training steps

---

## 🛠 Challenges & Future Work
### 🚧 Challenges Faced:
- **Imbalanced Data** – Most reviews are positive, making it harder to classify negatives.
- **Sarcasm & Ambiguity** – Some reviews contain mixed sentiments.
- **Feature Engineering** – Finding the best way to represent text features.

### 🔮 Future Enhancements:
- Train with **Deep Learning models** (LSTMs, BERT) for better context understanding.
- Deploy the model as a **web API** for real-time sentiment prediction.
- Use **TF-IDF and advanced embeddings** for richer feature representation.
