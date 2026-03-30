# 🔮 Next Word Predictor using LSTM

![Python](https://img.shields.io/badge/Python-3.12-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![NLP](https://img.shields.io/badge/Task-NLP-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Note

## This model is trained on the Hamlet dataset from the NLTK Gutenberg corpus.

---

## 🚀 Demo

<img width="1554" height="787" alt="image" src="https://github.com/user-attachments/assets/01590aa6-fc62-4518-a1d2-64faf80745ae" />


> 🔥 *Given an input sequence, the model predicts the most probable next word.*

---

## 📸 Screenshots

### 🔹 Training Process

<img width="1825" height="754" alt="image" src="https://github.com/user-attachments/assets/f55bd6a2-c4f9-490d-84cb-d760209cb3e7" />


### 🔹 Prediction Output

<img width="801" height="187" alt="image" src="https://github.com/user-attachments/assets/79d18564-c19e-4324-ae54-8ea64b62a59f" />


---

## 📌 Overview

This project implements a **Next Word Prediction system** using **LSTM (Long Short-Term Memory)** networks.
It learns sequential patterns in text data and predicts the most likely next word based on context.

The system demonstrates a complete **Natural Language Processing (NLP) pipeline** — from preprocessing to prediction.

---



## 🎯 Key Features

* Sequence-based prediction using LSTM
* Context-aware next word generation
* Efficient text preprocessing & tokenization
* Deep learning-based NLP model
* Clean and modular project structure

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy, Pandas**
* **NLTK**

---

## 📂 Project Structure

```
LSTM(project folder)/
│── hamlet.txt(data)/                 
│── Next_Word_Predictor_USing_LSTM.ipynb (model training)/            
│── lstm_rnn_model.keras , lstm_rnn_model.h5 (saved model)/  
│── app.py            
│── requirements.txt
            
```

---

## ⚙️ Installation

```bash
git clone https://github.com/Kushagra524/Next-Word-Predictor-using-LSTM.git
pip install -r requirements.txt
```

---

## ▶️ Usage

```cmd
python Next_Word_Predictor_USing_LSTM.ipynb        # Train the model

```

---

## 🔍 Model Architecture

* **Embedding Layer** → Converts words into dense vectors
* **LSTM Layer** → Captures sequential dependencies
* **Dense Layer** → Predicts next word (Softmax)

---

## 📊 Results

* Achieved strong contextual predictions
* Model effectively learns sentence structure

> 🔥 accuracy: 0.5584 - loss: 1.9433 - precision: 0.9384 - recall: 0.3281

---

## 🧠 Example

**Input:**

```text
Barn. In the same figure, like the
```

**Predicted Output:**

```text
King
```

---

## 🚀 Future Improvements

* Bidirectional LSTM / GRU
* Transformer-based models (GPT-style)
* Attention mechanisms
* Deployment using FastAPI / Streamlit

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork and improve.

---



## 👤 Author

**Kushagra Srivastava**
Deep Learning Engineer | NLP Engineer


