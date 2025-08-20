# IMDb Sentiment Analysis

## Overview
This project applies **supervised machine learning** to classify IMDb movie reviews as **positive** or **negative**.  
The dataset contains 50,000 reviews labeled by sentiment, making it a standard benchmark for sentiment analysis tasks.  

## Approach
- **Preprocessing**: Tokenization, stopword removal, and TF-IDF vectorization.  
- **Model**: Random Forest Classifier trained within a Scikit-learn Pipeline.  
- **Evaluation**: Accuracy, F1-score, and Confusion Matrix.  

## Results
- **Accuracy**: 84.3%  
- **F1-score**: 0.84  

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  

## Usage
1. Clone the repository and navigate to the project folder:
   ```bash
   git clone https://github.com/sidrekt/ds-ml-mini-projects.git
   cd ds-ml-mini-projects/imdb-sentiment-analysis
