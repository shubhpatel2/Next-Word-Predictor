LSTM Next Word Predictor
A simple Deep Learning project that learns from text and predicts the next word in a sentence.

🎯 What it does
You give it a sequence of words (like "The course follows a"), and it predicts the next likely word (like "monthly"). It was trained on Frequently Asked Questions (FAQ) data about a Data Science course.

📊 Key Results
Accuracy: ~96%

Training Loss: Very low (4.38)

Model Type: LSTM (Long Short-Term Memory) built with PyTorch

🛠️ Tools Used
Python

PyTorch (for the AI model)

NLTK (for processing text)

🚀 How to Run
Clone the repo:

Bash

git clone https://github.com/yourusername/lstm-next-word-predictor.git
Install libraries:

Bash

pip install torch numpy nltk
Run the notebook: Open pytorch_lstm_next_word_predictor.ipynb and run all cells.

📝 Example
Input: "What is the criteria to get"

Predicted Output: "certificate"
