
# Metaphor Analysis with RoBERTa

This project fine-tunes a **DistilRoBERTa model** for **metaphor detection** in text, inspired by T.S. Eliot's *The Love Song of J. Alfred Prufrock*.  
It demonstrates how large language models can be adapted for literary and cognitive semantic tasks.

## ✨ Features
- Uses Hugging Face's `distilroberta-base` as backbone.
- Fine-tuned for **binary sequence classification** (metaphor vs. non-metaphor).
- Includes evaluation with **accuracy, precision, recall, and F1-score**.
- Saves trained models for reuse (`./models/prufrock_roberta`).

## 📂 Project Structure
- `prufrok.convo_Roberta.(metaphor analysis with Roberta).ipynb` – main notebook with code.
- `models/prufrock_roberta/` – directory for saving trained models (auto-created).
- `data/` – expected dataset location (you can adapt to your own).

## 🛠 Requirements
Install dependencies:
```bash
pip install torch transformers datasets scikit-learn pandas numpy
