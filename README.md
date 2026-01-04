# IMDB Movie Reviews Sentiment Analysis

## Project Overview
This project predicts whether a movie review is **Positive** or **Negative** using the **IMDB Movie Reviews dataset**.  
It is a **beginner-level sentiment analysis project** suitable for college AIML selection.  

## Dataset
- 50,000 movie reviews from IMDB  
- Columns:  
  - `review` → text of the review  
  - `sentiment` → `positive` or `negative`  

## Steps
1. Load and preprocess the dataset  
2. Convert text into numbers using **CountVectorizer**  
3. Train a **Naive Bayes** model  
4. Evaluate accuracy and display confusion matrix  
5. Test predictions on new reviews  

## Requirements
- Python 3.x  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

Install libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
