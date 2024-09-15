# NLP-Project
**NLP Frequent Use Cases with Hugging Face Transformers**

This repository contains practical examples of how to use the Hugging Face Transformers library's models and pipelines to perform various Natural Language Processing (NLP) tasks. The examples cover a range of tasks, from sentiment analysis to machine translation, and are based on Hugging Face tutorials. The code is implemented using the latest pre-trained models available in the Transformers library.

**Activities**

**1. Named Entity Recognition (NER)**: This example demonstrates how to perform named entity recognition using the "dslim/bert-base-NER" model. The activity includes:

  Installing the Transformers package.
  Creating a pipeline for NER.
  Processing text to identify and filter entities such as people, organizations, and locations.
  
**2. Sentiment Analysis**: Here, we show how to perform sentiment analysis with the "distilbert-base-uncased-finetuned-sst-2-english" model. The activity includes:

  Setting up the pipeline for sentiment analysis.
  Evaluating two sentences to determine the predominant sentiment.
  
**3. Text Summarization**: In this example, we use the "sshleifer/distilbart-cnn-12-6" model for text summarization. The activity includes:

  Creating a pipeline for summarization.
  Summarizing a text excerpt to obtain a condensed version.
  
**4. Text Generation**: The "gpt2" model is used to generate text from an initial prompt. The activity includes:

  Setting up the pipeline for text generation.
  Generating a 500-word text from a given prompt.
  
**5. Question Answering**: This example demonstrates how to answer questions based on context using the "distilbert-base-cased-distilled-squad" model. The activity includes:

  Creating a pipeline for question answering.
  Answering a question based on a provided context.
  
**6. Translation**: Here, we use the "t5-base" model for translating text from English to French. The activity includes:

  Setting up the pipeline for translation.
  Translating a sentence from English to French.
  
**7. Masked Language Modeling**: In this example, the "distilbert-base-uncased" model is used to predict masked words in a sentence. The activity includes:

  Creating a pipeline for masked language modeling.
  Predicting options to fill in a masked word.
  
**8. Sentiment Analysis**: for Stock Market Headlines Using the "ProsusAI/finbert" model, this example evaluates the sentiment of stock market headlines. The activity includes:

  Setting up the pipeline for sentiment analysis.
  Evaluating financial headlines to determine sentiment.

**Requirements**

  Python 3.10 or higher
  Transformers library (installed with pip install transformers)

**References**

Hugging Face Transformers Documentation
