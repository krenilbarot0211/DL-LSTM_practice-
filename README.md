# DL-LSTM_practice
# Next Token Prediction using LSTM

📌 Project Overview

This project implements a Next Token Prediction model using LSTM (Long Short-Term Memory) for Natural Language Processing.
The model is trained on a dataset of quotes from famous scientists and learns the context of words to predict the **next token in a sequence.

The trained model can generate meaningful continuations of quotes by predicting the next word based on previous words.



🚀 Features

* Text preprocessing and cleaning
* Tokenization and sequence generation
* Word embedding representation
* LSTM-based deep learning model
* Next token prediction for quote generation
* Ability to generate meaningful quote completions



🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Natural Language Processing (NLP)



📂 Project Structure


Next-Token-Prediction-LSTM/
│
├── dataset/
│   └── quotes.csv
│
├── notebooks/
│   └── lstm_training.ipynb
│
├── models/
│   └── lstm_model.h5
│
├── src/
│   ├── preprocessing.py
│   ├── train_model.py
│   └── predict.py
│
├── requirements.txt
└── README.md


📊 Model Architecture

The model uses the following architecture:

1. Embedding Layer – Converts tokens into dense vector representations
2. LSTM Layer – Learns sequential dependencies in text
3. Dense Layer – Predicts probability distribution of the next token


🧪 Example

Input Sequence:


"The important thing is not to stop"


Predicted Output:

questioning


Generated Sentence:


"The important thing is not to stop questioning"


📈 Future Improvements

* Implement GRU and Transformer models for comparison
* Add temperature-based text generation
* Deploy using Streamlit for interactive quote generation
* Train on larger quote datasets

---

🎯 Learning Outcomes

Through this project, the following concepts were explored:

* Sequence modeling in NLP
* Tokenization and text preprocessing
* Deep learning using LSTM networks
* Next word prediction
* Text generation



👨‍💻 Author

Krenil
AI / Machine Learning Enthusiast
