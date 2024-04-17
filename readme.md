# Comparative Analysis of LSTM and DistilBERT Models for Sentiment Analysis on Yelp Reviews

## Overview
This project compares two advanced deep learning models—LSTM (Long Short-Term Memory) and DistilBERT (Distilled Bidirectional Encoder Representations from Transformers)—to perform sentiment analysis on Yelp reviews, focusing on restaurants and hotels. It evaluates these models based on accuracy, precision, recall, and F1 score, providing insights into the applicability of these technologies in real-world sentiment analysis tasks.

## Team Members
- Sajib (Ryhan) Suny: Model evaluation, literature review, and reporting
- Oluwadamilare Matthew Kolawole: Data preprocessing, tokenization, and hyperparameter tuning
- Noah Nsimbe: Implementation of DistilBERT model and tuning
- Amaka Genevieve Jane Awa: Base model creation and experiment setup

## Data
The dataset is derived from Yelp's Dataset Challenge, focusing on reviews specifically linked to the hospitality sector. Steps include:
- Text cleaning: Removing HTML tags and special characters
- Tokenization and lemmatization to refine the text
- Sentiment labeling based on star ratings: Positive (4-5 stars), Negative (1-2 stars), Neutral (3 stars)

## Models and Training
- **LSTM:** Suitable for processing sequences, remembering contextual information over long periods. The model uses an embedding layer, LSTM layer, dropout layers, and dense output layers.
- **DistilBERT:** A lighter version of BERT optimized for faster performance and less resource consumption, ideal for handling complex semantic relationships.

### Training Details
- Both models are trained using K-Fold cross-validation to ensure the models generalize well over unseen data.
- Detailed training results, hyperparameter tuning, and performance metrics are provided, showcasing the strengths and limitations of each model.

## Results
- **LSTM:** Achieved high accuracy with strengths in handling sequential data, especially for positive sentiments.
- **DistilBERT:** Demonstrated robust performance across various sentiment categories, particularly effective in dealing with nuanced language.

## Conclusion
Both models have shown efficacy in sentiment analysis with varying strengths:
- **LSTM** excels in sequential data handling.
- **DistilBERT** provides rapid processing and is capable of understanding complex language patterns.

## Repository Contents
- `data_processing.ipynb`: Preprocessing steps and initial data handling.
- `Lstm.ipynb`: Notebook containing the LSTM model implementation.
- `DistilBERT.ipynb`: Notebook for DistilBERT model implementation.
- `trainmodel.py`: Script for training the LSTM model.

## How to Use
1. Clone the repository.
2. Install dependencies as listed in `requirements.txt`.
3. Run the Jupyter notebooks to see the model implementations and experiments.

## References
- Detailed citations and references are provided, linking to studies and papers that underpin the methodologies and evaluations used in this project.

