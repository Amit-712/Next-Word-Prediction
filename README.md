# 📝 Next Word Prediction using LSTM

This project builds a **Next Word Prediction model** using *The Adventures of Sherlock Holmes* dataset (Project Gutenberg).  
It trains a deep learning model (LSTM) to predict the next word in a sequence of text.

---

## 📂 Project Structure
next-word-prediction/
├── data/
│   └── 1661-0.txt             # Dataset (Sherlock Holmes book)
├── notebooks/
│   └── Next_Word_Prediction.ipynb   # Jupyter Notebook with explanations
├── src/
│   └── next_word_prediction.py # Training + prediction script
├── requirements.txt            # Dependencies
├── README.md                   # Documentation
└── .gitignore


---

## ⚙️ Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/<your-username>/next-word-prediction.git
cd next-word-prediction
pip install -r requirements.txt
##  Usage
python src/next_word_prediction.py
Input : "sherlock holmes was"
Output: "sherlock holmes was not in the"

Input : "the king of"
Output: "the king of bohemia was in"
