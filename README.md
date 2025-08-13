# LSTM Word Prediction from Product Reviews

This project demonstrates how to train an LSTM-based language model to predict the next word in a sequence using a small dataset of product reviews in Turkish. The model uses an embedding layer, an LSTM layer, and a fully connected output layer. A simple grid search is implemented to test different hyperparameter combinations.

## Features
- Text preprocessing: lowercasing, punctuation removal, tokenization.
- Vocabulary creation and word-to-index mapping.
- LSTM architecture for word sequence modeling.
- Hyperparameter tuning with embedding size, hidden size, and learning rate.
- Word prediction function to generate a sequence of words from a starting word.

## Requirements
- Python 3.x
- PyTorch
- Collections (standard library)
- itertools (standard library)

## How It Works
1. Product review text is cleaned and tokenized.
2. Word pairs (or sequences) are generated for training.
3. The LSTM model is trained to predict the next word.
4. Grid search finds the best set of hyperparameters.
5. The final model generates predictions starting from a given word.

## Example Output
Start word: ürün
Predicted sequence: ürün beklentimi fazlasıyla

## Usage
```bash
pip install torch
python main.py
Replace main.py with your Python file containing the project code.

