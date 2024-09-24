# Sentiment Analysis Project

This project aims to build a sentiment analysis model with 2 models Decision Tree and Random Forest to classify text data as positive, negative. The project is implemented in Python and utilizes Jupyter Notebooks for code development and execution.

## Project Structure

- **assets/**: Directory containing supporting assets such as images or models used in the project.
- **data/**: Directory containing datasets used for training and testing the sentiment analysis model.
- **sentiment_analysis.ipynb**: Jupyter Notebook containing the code for sentiment analysis, including data preprocessing, model training, and evaluation.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/lbnm203/Sentiment-Analysis.git
   cd Sentiment-Analysis
2. Download the dataset

3. Download required library:
    ```bash
    pip install nltk
    pip install beautifulsoup4
    pip install contractions
## Data Processing

- Remove html tags
- Expand contractions (Expanding chatwords and contracts clearing contractions)
- Remove emoticons, symbols,  special characters
- Stopword removal, tokenization
- Remove punctuaion and make text lowercase
- Lemmatization

## Sentiment Classification
- The model will predict sentiment (positive/negative) after preprocessing the texts.
    
