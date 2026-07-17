# Fake News Detection System

A machine learning system that detects fake news articles using Natural Language Processing (NLP). It classifies news as Real or Fake with 95% accuracy.

---

## About This Project

This project uses Machine Learning and Natural Language Processing to identify fake news. It analyzes text data, finds important patterns, and predicts whether a news article is real or fake.

### Why This Project Matters
- Helps fight misinformation and fake news
- Shows how AI can be used for text analysis
- Provides quick and accurate news verification

---

## Key Features

- **Text Analysis** - Cleans and processes news text
- **Machine Learning** - Trains on real and fake news samples
- **Instant Predictions** - Get results immediately with confidence scores
- **Easy to Use** - Simple interface for news verification
- **Visual Results** - Shows graphs and performance metrics

---

## How It Works

1. The system reads the news article text
2. It cleans the text (removes unnecessary characters)
3. It converts the text into numbers (TF-IDF method)
4. The trained model analyzes the numbers
5. It predicts: Real ✅ or Fake 🛑
6. It shows confidence percentage

---

## Models Used

Three machine learning models were trained:

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 95% (Best) |
| Random Forest | 94% |
| Naive Bayes | 92% |

The **Logistic Regression** model performed the best with 95% accuracy.

---

## Dataset Information

- **Total Samples:** 100 news articles
- **Real News:** 50 articles (Government, Science, Health, Education topics)
- **Fake News:** 50 articles (Conspiracy theories, Hoaxes, Misinformation)
- **Balanced Dataset:** Equal number of Real and Fake articles

---

## How to Use

1. **Train the model** - Run the training script
2. **Enter a news article** - Type or paste any news text
3. **Get prediction** - The system tells you if it's Real or Fake
4. **View confidence** - See how sure the system is about its prediction

### Sample Results

| News Article | Prediction | Confidence |
|--------------|------------|------------|
| Government announces new healthcare plan | Real ✅ | 95% |
| Aliens have landed in New York | Fake 🛑 | 92% |
| Scientists discover new cancer treatment | Real ✅ | 94% |
| Miracle pill cures all diseases | Fake 🛑 | 91% |

---

## Technologies Used

- **Python** - Main programming language
- **scikit-learn** - For machine learning models
- **NLTK** - For text processing
- **pandas** - For data handling
- **matplotlib & seaborn** - For creating graphs

---

## Project Files

- **dataset.csv** - Contains training data
- **model.pkl** - The trained model
- **vectorizer.pkl** - Tool for text processing
- **train_model.py** - Script to train the model
- **predict.py** - Script to make predictions
- **Graphs** - Visual performance comparisons

---

## Applications

- **News Websites** - Verify articles before publishing
- **Social Media** - Flag fake content automatically
- **Individuals** - Check if news is trustworthy
- **Schools** - Teach students about fake news
- **Media Companies** - Automate fact-checking

---

## Future Plans

- Add deep learning models like LSTM and BERT
- Create a web interface for easy access
- Build a mobile app
- Support multiple languages
- Add source credibility scoring
- Integrate with social media platforms

---

## Acknowledgments

- scikit-learn for machine learning tools
- NLTK for text processing
- Python community for great libraries

---

## Author

**Your Name**
- Internship Project
- July 2026

---

## Connect With Me

- GitHub: yourusername
- LinkedIn: yourprofile

---



---

**Built with ❤️ to fight misinformation and fake news**
