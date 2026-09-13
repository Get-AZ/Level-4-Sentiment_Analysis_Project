# Sentiment Analysis with DistilBERT

A production-ready NLP sentiment-analysis application using
DistilBERT and Streamlit.

## Project Overview

This project develops and evaluates multiple approaches to binary
sentiment classification using the IMDB movie-review dataset.

The project progressed from classical TF-IDF machine learning models
to transformer-based sentiment classification using DistilBERT.

The final application provides sentiment predictions and confidence
scores through an interactive Streamlit dashboard.

## Final Model

**DistilBERT**

### Performance

| Metric | Score |
|---|---:|
| Accuracy | 91.97% |
| Precision | 91.90% |
| Recall | 92.12% |
| F1 Score | 92.01% |
| ROC-AUC | 97.49% |

## TF-IDF vs DistilBERT

| Metric | TF-IDF | DistilBERT | Improvement |
|---|---:|---:|---:|
| Accuracy | 90.04% | 91.97% | +1.93 pp |
| Precision | 89.32% | 91.90% | +2.58 pp |
| Recall | 90.96% | 92.12% | +1.16 pp |
| F1 Score | 90.13% | 92.01% | +1.88 pp |
| ROC-AUC | 96.50% | 97.49% | +0.99 pp |

DistilBERT improved over the TF-IDF baseline across every tracked
evaluation metric.

## Confidence Reliability

- Average confidence: 98.35%
- Correct prediction confidence: 98.87%
- Incorrect prediction confidence: 92.48%
- Confidence gap: 6.38 percentage points
- Recommended threshold: 70%
- Coverage at threshold: 98.51%
- Accuracy at threshold: 92.51%

## Features

- DistilBERT sentiment classification
- Positive / Negative prediction
- Probability calculation
- Confidence scoring
- Confidence thresholding
- Streamlit interface
- Batch review processing
- Model comparison
- Reproducibility artifacts
- SHA256 model integrity validation

## Technology Stack

- Python
- PyTorch
- Hugging Face Transformers
- DistilBERT
- Streamlit
- pandas
- NumPy
- scikit-learn

## Project Workflow

1. Dataset loading
2. Exploratory data analysis
3. Text cleaning
4. Tokenization
5. TF-IDF feature engineering
6. Classical ML baseline models
7. N-gram experiments
8. Word embeddings
9. Transformer preparation
10. DistilBERT fine-tuning
11. Model evaluation
12. Confidence analysis
13. Streamlit deployment
14. Release validation
15. Production packaging

## Running the Application

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Streamlit:

```bash
streamlit run app.py
```

## Model Files

Large model files are intentionally excluded from GitHub through
`.gitignore`.

The validated release package contains the production model, best
model, tokenizer, deployment application, documentation, and
integrity hashes.

## Project Status

**Production Ready**

Release validation: **PASSED**

## License

MIT License

## Author

Sentiment Analysis Machine Learning Project
