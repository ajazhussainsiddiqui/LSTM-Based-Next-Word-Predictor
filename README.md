# LSTM Next Word Predictor

This project implements an LSTM-based model in PyTorch to predict the next word in a sentence. It's trained on a dataset of Q&A text from a Data Science Mentorship Program FAQ.

## Key Features
- Tokenization using NLTK.
- LSTM model with embedding layer (vocab size: 289, hidden size: 150).
- Trained for 50 epochs with Adam optimizer (LR: 0.001).
- Example: Input "data" → Predicts "analysis".

## Setup
1. Install dependencies: `pip install torch nltk numpy`.
2. Download NLTK data: Run `nltk.download('punkt')` in the notebook.
3. Train the model and generate predictions.

## Results
- Final training loss: ~4.41 after 50 epochs.
- Generates coherent next words in context (e.g., "This is to clarify that placement assistance does not mean...").
