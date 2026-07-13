# IMDb Sentiment Analysis using LSTM

A deep learning project for binary sentiment classification of movie reviews using a Long Short-Term Memory (LSTM) network implemented with TensorFlow/Keras.

## Overview

This project builds an end-to-end Natural Language Processing (NLP) pipeline for sentiment analysis on the IMDb Movie Reviews dataset. The workflow includes data preprocessing, text tokenization, sequence padding, model training, evaluation, and visualization of learning performance.

The objective is to classify movie reviews as **Positive** or **Negative** using an LSTM-based neural network.

---

## Features

- Text preprocessing and cleaning
- Tokenization and vocabulary construction
- Sequence padding
- LSTM-based sentiment classification
- Model evaluation
- Training visualization
- Confusion matrix generation

---

## Project Structure

```
imdb-lstm-sentiment-analysis/
│
├── imdb_lstm.ipynb
├── images/
│   ├── sentiment_distribution.png
│   ├── review_length_distribution.png
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Dataset

This project uses the **IMDb Large Movie Review Dataset**, which contains 50,000 movie reviews equally divided into positive and negative sentiments.

The dataset is publicly available from:

https://ai.stanford.edu/~amaas/data/sentiment/

> The dataset is **not included** in this repository.

---

## Model Architecture

```
Input Reviews
      │
Tokenizer
      │
Padding
      │
Embedding Layer
      │
LSTM Layer
      │
Dropout
      │
Dense (Sigmoid)
      │
Prediction
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/aquene12345-ship-it/imdb-lstm-sentiment-analysis.git
cd imdb-lstm-sentiment-analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Open the notebook

```bash
jupyter notebook imdb_lstm.ipynb
```

Run all cells sequentially to:

- Load the dataset
- Preprocess text
- Train the LSTM model
- Evaluate the model
- Generate visualizations

---

## Results

The notebook generates:

- Sentiment distribution
- Review length distribution
- Training & validation accuracy
- Training & validation loss
- Confusion matrix

Example outputs are stored in the **images/** directory.

---

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Notes

Model weights and the IMDb dataset are excluded from this repository to reduce repository size.

Please download the dataset from the official source before running the notebook.

---

## Author

Vo Quoc Khanh

Artificial Intelligence Student

FPT University