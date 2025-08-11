# 🌐 Language Detection Model

A language detection model automatically identifies the language of a given text — e.g., detecting `"Hola"` as Spanish or `"Bonjour"` as French.

---

## 🔧 How It Works

1. **Preprocessing**: Clean and normalize text.
2. **Feature Extraction**: Use character n-grams, stop words, word frequencies.
3. **Classification**: Apply ML/DL models to predict the language.

---

## 🤖 Types of Models

- **Rule-Based** (dictionaries, heuristics)
- **Statistical** (n-gram + Naive Bayes)
- **ML/DL** (SVM, LSTM, Transformers)
- **Pretrained Libraries**: `langdetect`, `langid.py`, `FastText`, `CLD2/3`

---

## ⚙️ Example (`langdetect`)

```python
from langdetect import detect
print(detect("Ceci est un texte en français."))  # Output: 'fr'

