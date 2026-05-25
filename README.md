# BERT Toxic Comment Classification

## Project Overview
This project fine-tunes the BERT transformer model on the Jigsaw Toxic Comment dataset for multi-label toxic comment classification.

The model predicts:
- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

---

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## Workflow
Raw Text → Preprocessing → Tokenization → BERT Fine-Tuning → Evaluation → Prediction

---

## Model Used
- bert-base-uncased

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Sample Prediction

Input:
"You are a horrible person"

Output:
toxic: 0.9202
insult: 0.5541
obscene: 0.5031

---

## Dataset
Jigsaw Toxic Comment Classification Dataset from Kaggle.

---

## Results
The model successfully learned contextual toxic language patterns and performed multi-label toxicity classification effectively.

---
