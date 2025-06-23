# 🏰 Disneyland Visitor Reviews — NLP Analysis

This project applies **Natural Language Processing (NLP)** techniques to analyze over **42,000 TripAdvisor reviews** from three Disneyland parks: Hong Kong, Paris, and California. The goal is to uncover patterns in visitor sentiment and extract actionable insights to improve the customer experience.

📘 [View the full analysis in Google Colab](https://colab.research.google.com/drive/1Hli6gd91P4s0CcOgrsHHO0XcE3pEqiOU?usp=sharing)

---

## 📌 Research Question

**How can NLP analysis of visitor reviews help improve customer experience at Disneyland?**

---

## 📊 Dataset

- Source: [Kaggle – Disneyland Reviews](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews)
- Locations: Hong Kong, Paris, California
- Sample size: **42,656 reviews**
- Star ratings: 1–5 (focus on **1-star and 5-star reviews** for sentiment contrast)

---

## 🔍 Methods & Techniques

- Text Preprocessing: cleaning, stopword removal, lemmatization  
- Word Frequency Analysis: single-word and bigram word clouds  
- Monthly Review Trends: sentiment over time  
- Sentiment Analysis: using a distilled version of **Google’s GoEmotions** model  
- Topic Modeling: LDA for discovering recurring complaint themes  

---

## 🎯 Key Insights

### 1-star Reviews:
- ⏳ Long queues and wait times  
- 🧍 Overcrowding  
- 💸 High prices & poor value  
- 🙁 Customer service issues  
- ❌ Ride closures

### 5-star Reviews:
- 🎢 Enjoyable attractions and rides  
- 👨‍👩‍👧‍👦 Family-friendly environment  
- 🎉 Great shows and entertainment  
- 💖 Overall satisfaction and “Disney magic”

---

## 📆 Seasonal Analysis

- **Paris**: Highest proportion of negative reviews; issues peak in March, June, August  
- **California**: Most positive reviews, with stable performance year-round  
- **Hong Kong**: Balanced sentiment, but August has more 1-star ratings (weather-related)

---

## 💡 Recommendations

- Implement **virtual queues** or ticket caps during peak seasons  
- Improve **ride availability** and **staff interaction**  
- Upgrade **food quality** and **customer service training**  
- Offer **value-based pricing** or fast-track upgrades

---

## 🚀 How to Run

### Option 1: Run on Google Colab (Recommended)
1. Open the notebook: https://colab.research.google.com/drive/1Hli6gd91P4s0CcOgrsHHO0XcE3pEqiOU?usp=sharing
2. Duplicate to your Google Colab
3. Make sure the runtime is set to Python 3
4. Run all cells step by step

### Option 2: Run Locally

- Clone the repo
git clone [https://github.com/your-username/disneyland-nlp-review.git](https://github.com/xuefeiwang001/Natural_Language_Processing-Disneyland_reviews.git) <br>
cd disneyland-nlp-review

- (Optional) Create a virtual environment
python -m venv venv <br>
source venv/bin/activate  # or venv\Scripts\activate on Windows

- Install dependencies
pip install -r requirements.txt

- Run the notebook
jupyter notebook <br>
Open Natural_Language_Processing_Disneyland_reviews.ipynb and execute the cells.

---

## 🧪 Tech Stack
- Python 3.8+
- Pandas / NumPy
- NLTK / spaCy
- Scikit-learn
- Gensim (LDA)
- Hugging Face Transformers (distilbert-base-uncased-go-emotions-student)
- Matplotlib / Seaborn / WordCloud

---

## 📁 Project Structure
- Natural_Language_Processing_Disneyland_reviews.ipynb
- NLP - Disneyland Review Analysis Report.pdf
- README.md

---

## 📄 License
This project is shared under the MIT License

---

## 👩‍💻 Author
Xuefei Wang <br>
📘 MSc in Data Analytics and AI <br>
🔍 Driven to transform raw data into strategic insights that lead to real impact. <br>
📧 [xuefei.wang001@qq.com]


