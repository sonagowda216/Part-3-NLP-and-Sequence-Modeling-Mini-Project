# Part 3: NLP and Sequence Modeling Mini Project

## Overview
Build an NLP pipeline to classify customer support messages by sentiment (positive/neutral/negative).

## Dataset
customer_support_text_classification.csv — Customer support tickets with sentiment_label target.

## Folder Structure
```
part-3-nlp-sequence-modeling/
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_evaluation.png
    ├── model_evaluation.csv
    └── sample_predictions.txt
```

## Tasks
1. Dataset Understanding
2. Text Preprocessing (lowercase, remove punctuation)
3. Text Vectorization (TF-IDF)
4. Baseline Model (Logistic Regression)
5. Sequence Model (LSTM with Keras Embedding)
6. Reflection on RNNs, LSTMs, Attention, and Transformers

## How to Run
```
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
