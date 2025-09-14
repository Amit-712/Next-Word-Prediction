"""
Next Word Prediction using LSTM
Author: Amit Singh
Resume Project
"""

# ---------------------------
# Requirements (for requirements.txt)
# ---------------------------
# tensorflow==2.17.0
# numpy

# ---------------------------
# README.md content
# ---------------------------
"""
# 📝 Next Word Prediction using LSTM

This project builds a **Next Word Prediction model** using *The Adventures of Sherlock Holmes* dataset (Project Gutenberg).  
It trains a deep learning model (LSTM) to predict the next word in a sequence of text.

## Project Structure
.
├── 1661-0.txt              # Dataset (Sherlock Holmes book)
├── next_word_prediction.py  # Main script
├── requirements.txt         # Dependencies
└── README.md                # Project documentation

## Installation
Clone this repository and install dependencies:
git clone https://github.com/<your-username>/next-word-prediction.git
cd next-word-prediction
pip install -r requirements.txt

## Usage
python next_word_prediction.py

Example predictions:

Input : "sherlock holmes was"
Output: "sherlock holmes was not in the"

Input : "the king of"
Output: "the king of bohemia was in"

## Model
- Architecture: Embedding → LSTM → Dense (Softmax)
- Sequence length: 5 words → predict next word
- Loss: Categorical Crossentropy
- Optimizer: Adam

## Evaluation
- Accuracy: ~XX% (depends on training epochs & dataset)
- Perplexity: ~YY (lower = better)

## Future Improvements
- Use GRU or Transformer models (BERT/GPT-style)
- Deploy as a Flask API or Streamlit app for interactive predictions
- Train on larger corpora for better generalization

## Dataset
- Source: The Adventures of Sherlock Holmes by Arthur Conan Doyle
- Available on Project Gutenberg

## Author
Amit Singh
B.Tech CSE, Punjabi University Patiala (2026)
LinkedIn: https://www.linkedin.com/in/amit712
"""
