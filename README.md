# 📰 Fake News Prediction

This project uses Natural Language Processing (NLP) and machine learning techniques to classify news articles as **real** or **fake**.

## 📁 About the Dataset

- `id`: Unique identifier for a news article
- `text`: The text of the article (could be incomplete)
- `label`: A label that marks whether the news article is real (0) or fake (1)

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

## 🧹 Data Preprocessing

- Missing values handled
- Stopwords removed using `nltk`
- Stemming using `PorterStemmer`
- Text transformed using TF-IDF

## 🧠 Model

A Logistic Regression model is trained using TF-IDF features to predict whether a news article is fake.

## 📊 Accuracy

- **Training Accuracy**: 95% (example)
- **Testing Accuracy**: 89% (example)

## 📈 Visualization

Bar plots and heatmaps used to explore dataset and model performance.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fake-news-prediction.git
   cd fake-news-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook fakeNews.ipynb
   ```

## 📬 Contact

For questions, feel free to reach out at [your-email@example.com](mailto:your-email@example.com).
