# English to Urdu Translation Transformer Model

## Project Description:

This project implements a Transformer-based neural machine translation (NMT) model to translate text from English to Urdu. The model is trained from scratch using the Hugging Face Transformers and Datasets libraries.

The purpose of this project is to build a working translation system that can convert English sentences into Urdu accurately by learning from a parallel English-Urdu dataset.

---

## What I Did

- Loaded and prepared a parallel English-Urdu dataset containing sentence pairs.
- Preprocessed and tokenized the English (source) and Urdu (target) sentences using a tokenizer compatible with the Transformer model.
- Defined the Transformer sequence-to-sequence model architecture for translation.
- Configured training parameters like epochs, batch size, and logging.
- Trained the model on the tokenized dataset.
- Saved the trained model and tokenizer for later use.

---

## Requirements

- Python 3.7 or higher
- `transformers` library
- `datasets` library
- `torch` (PyTorch framework)
- `sentencepiece` (if required by the tokenizer)

Install the required libraries with:

```bash
!pip install transformers datasets sentencepiece --quiet
