# NLP Tasks with Hugging Face Transformers

This repository showcases three core NLP tasks implemented using Hugging Face's Transformers API. Each task is explored in a separate Jupyter notebook, demonstrating model loading, fine-tuning, and evaluation on relevant datasets.

## 📁 Contents

- `classification.ipynb` — Sentiment Classification
- `NER.ipynb` — Named Entity Recognition (NER)
- `MCQ.ipynb` — Multiple Choice Question Answering

---

## 📝 Task Overview

### 1. Sentiment Classification (`classification.ipynb`)
- **Model Used**: `rbt3` (RoBERTa-wwm-ext)
- **Architecture**: `AutoModelForSequenceClassification`
- **Dataset**: Chinese review texts
- **Objective**: Train the model to classify reviews as **positive** or **negative**.

### 2. Named Entity Recognition (`NER.ipynb`)
- **Model Used**: `chinese-macbert-large`
- **Architecture**: `AutoModelForTokenClassification`
- **Dataset**: People's Daily annotated articles
- **Objective**: Identify and label entities (e.g., persons, locations, organizations) within Chinese sentences.

### 3. Multiple Choice Question Answering (`MCQ.ipynb`)
- **Model Used**: `chinese-macbert-base`
- **Architecture**: `AutoModelForMultipleChoice`
- **Dataset**: [CLUE C3 dataset](https://huggingface.co/datasets/clue/clue/viewer/c3/test?p=1&row=6)
- **Objective**: Train the model to answer multiple-choice questions based on short passages.

