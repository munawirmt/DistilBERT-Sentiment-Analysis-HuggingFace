# DistilBERT Sentiment Analysis using Hugging Face

A simple and efficient Python script to perform **Sentiment Analysis** using Hugging Face's `transformers` pipeline. This project leverages pre-trained BERT-based models to classify the emotional tone of input text.

## Features
- **State-of-the-art NLP:** Uses transformer models for high-accuracy sentiment prediction.
- **Minimal Code:** Achieves tokenization, model loading, and inference in just a few lines.
- **Instant Insights:** Provides both the sentiment label (POSITIVE/NEGATIVE) and the confidence score.

## How to Run
1. Install the required dependencies:
   ```bash
   pip install transformers torch
   ```
2. Run the script to analyze any custom text.

## Example Output
For the input `"I love learning AI"`, the model outputs:
```python
[{'label': 'POSITIVE', 'score': 0.9998}]
```
