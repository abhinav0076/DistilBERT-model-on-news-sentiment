DistilBERT-Based Sentiment Analysis Model
This repository contains a fine-tuned DistilBERT model for sentiment analysis on a disaster-related text dataset. The model classifies whether a given text indicates a disaster (1) or not (0).

Key Features:
Built using the Hugging Face Transformers library and PyTorch.
Tokenization with DistilBertTokenizer and fine-tuning of DistilBertForSequenceClassification.
Handles preprocessing, training, and evaluation with minimal effort using the Trainer API.
Evaluated on a validation set with metrics like accuracy, classification report, and confusion matrix.
