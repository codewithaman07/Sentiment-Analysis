# Twitter Sentiment Analysis

## Overview

This project performs **Sentiment Analysis on Twitter Data** using **Machine Learning** techniques. It classifies tweets as **positive or negative** based on their content. The dataset used is **Sentiment140**, which contains labeled tweets.

## Features

- **Preprocessing**: Cleans tweets by removing URLs, mentions, hashtags, and special characters.
- **Feature Engineering**: Uses **TF-IDF Vectorization** to convert text into numerical form.
- **Model Training**: Implements **Logistic Regression** for classification.
- **Evaluation**: Assesses model performance using accuracy, precision, recall, and F1-score.

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **NLTK**
- **Scikit-learn**

## Dataset

The dataset used is **Sentiment140**, which contains 1.6 million labeled tweets:

- `0`: Negative sentiment
- `1`: Positive sentiment
- The dataset includes **tweet text, polarity, and metadata**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset and place it in the project directory.

## Usage

1. **Preprocess the data**
   ```bash
   python preprocess.py
   ```
2. **Train the model**
   ```bash
   python train.py
   ```
3. **Evaluate the model**
   ```bash
   python evaluate.py
   ```
4. **Make predictions**
   ```bash
   python predict.py --text "I love this product!"
   ```

## Results

- **Accuracy:** \~85%
- **F1-score:** High performance on both positive and negative tweets.

## Future Improvements

- Add **deep learning models** (LSTMs, Transformers)
- Implement **real-time Twitter API** integration
- Enhance **text preprocessing** with advanced NLP techniques


