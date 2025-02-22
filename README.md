# LLM-finetuning-Sentiment-Analysis
This project demonstrates how to fine-tune a language model for binary sentiment classification using the IMDB-truncated dataset. The model utilizes **DistilBERT** and applies **LoRA (Low-Rank Adaptation)** for efficient fine-tuning. The training is performed using the Hugging Face `transformers` and `peft` libraries.

## 📋 Features
- Loads and tokenizes the IMDB-truncated dataset.
- Fine-tunes a pre-trained DistilBERT model for sentiment classification.
- Applies **LoRA** for parameter-efficient fine-tuning.
- Evaluates the model using accuracy as the primary metric.
- Predicts sentiment for custom text inputs before and after training.
