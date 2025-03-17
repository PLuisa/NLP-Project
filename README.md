# NLP Frequent Use Cases with Hugging Face Transformers

This repository showcases multiple Natural Language Processing (NLP) tasks using Hugging Face's pre-trained Transformer models. Each activity demonstrates a common NLP use case, making it easier to apply state-of-the-art machine learning models in real-world applications.

## 🚀 Activities

### 1️⃣ Named Entity Recognition (NER)  
- **Model Used:** `dslim/bert-base-NER`  
- **Description:** Identifies entities such as people, organizations, and locations in a given text.

### 2️⃣ Sentiment Analysis  
- **Model Used:** `distilbert-base-uncased-finetuned-sst-2-english`  
- **Description:** Classifies the sentiment (positive/negative) of sentences.

### 3️⃣ Text Summarization  
- **Model Used:** `sshleifer/distilbart-cnn-12-6`  
- **Description:** Summarizes long texts into concise versions.

### 4️⃣ Text Generation  
- **Model Used:** `gpt2`  
- **Description:** Generates text from a given prompt.

### 5️⃣ Question Answering  
- **Model Used:** `distilbert-base-cased-distilled-squad`  
- **Description:** Answers questions based on a given context.

### 6️⃣ Translation  
- **Model Used:** `t5-base`  
- **Description:** Translates English text into French.

### 7️⃣ Masked Language Modeling  
- **Model Used:** `distilbert-base-uncased`  
- **Description:** Predicts masked words in a sentence.

### 8️⃣ Sentiment Analysis for Stock Market Headlines  
- **Model Used:** `ProsusAI/finbert`  
- **Description:** Analyzes sentiment in financial news headlines.

## 🛠 Installation

To run this project, install the necessary dependencies:

```bash
pip install transformers torch librosa
```

If running in Google Colab, simply execute the notebook cells.

## 📌 Example Usage

```python
from transformers import pipeline

# Load a sentiment analysis model
classifier = pipeline("sentiment-analysis")

# Analyze a sentence
result = classifier("I love this project!")
print(result)
```

## 📖 References
- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers)

## 🤝 Feedback & Contributions
Feel free to open an issue or submit a pull request to improve this project!

