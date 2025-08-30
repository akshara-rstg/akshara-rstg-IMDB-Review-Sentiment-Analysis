# Sentiment Analysis on IMDb Reviews 

This project focuses on building a **Sentiment Analysis** system using IMDb reviews. The dataset contains 50,000 reviews labeled as positive or negative.  
We experimented with multiple Machine Learning models and compared their performance.

##  Project Overview

- **Goal:** Classify movie reviews as **Positive** or **Negative**
- **Dataset:** IMDb Movie Reviews (50k reviews)
- **Tech Stack:**
  - Python 🐍
  - Scikit-learn
  - NLTK
  - Matplotlib / Seaborn (for visualization)

##  Steps Performed

1. **Data Preprocessing**
   - Lowercasing
   - Removing stopwords, punctuation, HTML tags
   - Lemmatization
   - Tokenization
2. **Feature Engineering**
   - Bag of Words (BoW)
   - TF-IDF Vectorization
3. **Models Trained**
   - Multinomial Naive Bayes
   - Logistic Regression
   - Support Vector Classifier (SVC)
   - Voting Classifier (Ensemble)

##  Model Performance

| Model                        | Train Accuracy | Test Accuracy | Precision | Recall | F1-Score |
|------------------------------|----------------|---------------|-----------|--------|----------|
| Multinomial Naive Bayes      | 90.35%         | 87.87%        | 87.88%    | 87.87% | 87.87%   |
| Logistic Regression          | 93.37%         | 89.74%        | 89.76%    | 89.74% | 89.73%   |
| Support Vector Classifier    | 98.85%         | 89.69%        | 89.69%    | 89.69% | 89.69%   |
| **Voting Classifier (Ensemble)** | **94.97%**    | **89.97%**    | **89.98%**| **89.97%** | **89.97%** |

**Best Model:** **Voting Classifier (Ensemble)**

##  Confusion Matrices

Confusion matrices for each classifier are plotted and saved in the `plots/` folder.

##  Future Improvements

- Try **Deep Learning (LSTMs / Transformers like BERT)**
- Hyperparameter Tuning
- Handle sarcasm/complex sentiments better

## 📂 Project Structure
