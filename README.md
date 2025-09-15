# Resume Named Entity Recognition (NER) with Hugging Face

## 📌 Overview
This project fine-tunes **BERT (bert-base-cased)** on the CoNLL-2003 dataset for **Named Entity Recognition (NER)**.
The same pipeline can be applied to **resume parsing** (extracting skills, degrees, companies, job titles).

## 🚀 Features
- Fine-tuned Transformer (BERT) for token classification
- Interactive Gradio demo
- Ready for Hugging Face Spaces

## 🛠️ Tech Stack
- Python, PyTorch
- Hugging Face Transformers
- Gradio
- Google Colab

## 📊 Example
**Input**
John Doe worked at Google as a Software Engineer after studying at Stanford University.

**Output**
```json
[
  {"entity": "PER", "word": "John Doe"},
  {"entity": "ORG", "word": "Google"},
  {"entity": "JOB", "word": "Software Engineer"},
  {"entity": "LOC", "word": "Stanford University"}
]
Model:https://huggingface.co/soh7/bert-finetuned-ner 

Demo: https://huggingface.co/spaces/soh7/bert-finetuned-ner 

Code: https://github.com/sohamgupta779-art/bert-finetuned-ner.git
