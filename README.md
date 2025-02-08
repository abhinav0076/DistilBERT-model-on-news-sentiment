DistilBERT-Based Sentiment Analysis Model


This repository contains a fine-tuned DistilBERT model for sentiment analysis on a disaster-related text dataset. The model classifies whether a given text indicates a disaster (1) or not (0).

Key Features:
Built using the Hugging Face Transformers library and PyTorch.
Tokenization with DistilBertTokenizer and fine-tuning of DistilBertForSequenceClassification.
Evaluated on a validation set with metrics like accuracy, classification report, and confusion matrix.

Requirements:

torch>=1.12.0
transformers>=4.25.0
datasets>=2.7.0
scikit-learn>=1.1.3
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.3
seaborn>=0.11.2
