# Transformer-Based Sentiment Analysis — DistilBERT

**Role:** Machine Learning / NLP Project

**Technologies:** Python · NLP · Hugging Face Transformers · DistilBERT ·
PyTorch · Scikit-learn · Streamlit · Git · GitHub

## Project Summary

Designed and implemented an end-to-end binary sentiment-analysis system
for movie reviews, progressing from a classical TF-IDF baseline to a
fine-tuned DistilBERT Transformer model.

The project combined model development, quantitative benchmarking,
confidence analysis, inference engineering, reproducibility,
documentation, and controlled GitHub release management.

## Modeling and Evaluation

- Established a TF-IDF baseline achieving **90.04% accuracy**.
- Developed and evaluated a fine-tuned DistilBERT binary
  text-classification model.
- Achieved **91.97% accuracy, 91.90% precision, 92.12% recall,
  92.01% F1, and 97.49% ROC-AUC**.
- Measured an observed **1.93 percentage-point accuracy improvement**
  over the evaluated TF-IDF baseline.
- Evaluated multiple complementary classification metrics.

## Confidence and Reliability Analysis

- Evaluated prediction confidence in addition to conventional metrics.
- Validated a recommended **70% confidence threshold**.
- Achieved **98.51% coverage and 92.51% accuracy** at that threshold.
- Measured overall average confidence of **98.35%**.
- Correct predictions averaged **98.87% confidence**.
- Incorrect predictions averaged **92.48% confidence**.
- Identified a **6.38 percentage-point confidence gap**.
- Identified **307 high-confidence errors**, demonstrating that
  confidence is not a guarantee of correctness.

## Transformer Inference Engineering

Implemented inference using:

- Hugging Face Transformers
- PyTorch
- DistilBERT
- AutoTokenizer
- AutoModelForSequenceClassification
- Softmax probability processing
- Streamlit

The inference workflow accepts review text and returns predicted
sentiment, probability, and confidence.

## Application / Deployment

Packaged the validated inference workflow as a Streamlit application.

Architecture:

Review Text
→ Streamlit
→ Tokenizer
→ DistilBERT
→ PyTorch Inference
→ Probabilities
→ Sentiment / Confidence

## Reproducibility and Release Engineering

- Organized a professional GitHub release containing 13 validated files.
- Included documentation, results, usage, requirements, release notes,
  portfolio material, and reproducibility/audit evidence.
- Protected large trained-model artifacts through .gitignore rules.
- Verified SHA256 integrity for important release documentation.
- Performed local-versus-remote GitHub consistency checks.
- Verified published commit, repository tree, documentation, metrics,
  architecture, and release scope.
- Performed a final post-publication audit.

## Final Release

Repository:

Get-AZ/Level-4-Sentiment_Analysis_Project

Final published commit:

360f23fb2e1f65b154084269ff8c2bfc728b7906

## Technical Skills

**Machine Learning:** Binary Classification · Model Benchmarking ·
Model Evaluation · Performance Analysis

**NLP:** Sentiment Analysis · TF-IDF · Text Classification ·
Transformer Models

**Deep Learning:** DistilBERT · PyTorch · Fine-Tuned Transformers

**Model Reliability:** Confidence Analysis · Threshold Evaluation ·
Coverage Analysis · Error Analysis

**Inference Engineering:** AutoTokenizer ·
AutoModelForSequenceClassification · Softmax · Streamlit

**ML Engineering:** Reproducibility · Artifact Integrity ·
Documentation · Release Validation

**Software / Version Control:** Python · Git · GitHub · SSH ·
.gitignore Governance · SHA256 Verification
