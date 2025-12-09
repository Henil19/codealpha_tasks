# FAQ Chatbot (TF-IDF + Cosine Similarity)

This project is an FAQ Chatbot that takes a user question, preprocesses it with spaCy NLP, converts FAQ questions into TF-IDF vectors, and finds the most similar FAQ using cosine similarity.

## Files
- `chatbot_for_faqs.py` — Main script (cleaned from original Colab export).
- `faqs.csv` — Example FAQ dataset used by the script.
- `requirements.txt` — Python dependencies.

## Quick start (Colab)
1. Open a Colab notebook and upload these files.
2. Install dependencies:
```bash
!python -m pip install --upgrade pip setuptools wheel
!pip install -q spacy==3.8.0 scikit-learn==1.4.2 pandas==2.2.2 joblib==1.3.2
!python -m spacy download en_core_web_sm

