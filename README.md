# Turkish News Categorization & Sentiment Analysis using BERT-turk

This repository contains an end-to-end Natural Language Processing (NLP) pipeline designed to preprocess unstructured Turkish text data, clean and tokenize text patterns, and execute deep text classification. The system fine-tuned a pre-trained **BERT-turk** transformer model to achieve high-accuracy news categorization and sentiment classification.

## Key Features
- **Robust Preprocessing:** Custom text cleaning pipeline to strip punctuation, remove stopwords, and normalize Turkish characters.
- **Efficient Tokenization:** Handled dynamic string inputs using the Hugging Face `BertTokenizer` with structural padding and truncation.
- **Transformer Optimization:** Fine-tuned the `dbmdz/bert-base-turkish-cased` architecture using PyTorch and Hugging Face Transformers.

## Tech Stack
- **Language:** Python
- **Deep Learning Framework:** PyTorch, Hugging Face (Transformers)
- **Data Engineering:** Pandas, NumPy
- **NLP Tools:** Scikit-learn, NLTK
