# Transformer-Based Sentiment Analysis with DistilBERT

## Executive Summary

Built and validated a Transformer-based binary sentiment-classification
system for movie reviews using DistilBERT, Hugging Face Transformers,
and PyTorch.

The project progressed from a classical TF-IDF baseline to a fine-tuned
Transformer model, followed by multi-metric evaluation, confidence and
reliability analysis, Streamlit inference packaging, and controlled
GitHub release validation.

## Problem

The project addresses binary sentiment classification of movie reviews:

- Positive
- Negative

## Objective

Develop a reproducible end-to-end NLP workflow covering:

1. Classical NLP baseline
2. Transformer-based modeling
3. Quantitative comparison
4. Multi-metric evaluation
5. Confidence/reliability analysis
6. Inference application
7. Reproducibility
8. Controlled release engineering

## Technical Approach

TF-IDF Baseline
→ DistilBERT Fine-Tuning
→ Multi-Metric Evaluation
→ Confidence Analysis
→ Streamlit Inference
→ Controlled GitHub Release
→ Post-Publication Audit

## Certified Results

| Metric | Result |
|---|---:|
| Accuracy | 91.97% |
| Precision | 91.90% |
| Recall | 92.12% |
| F1 Score | 92.01% |
| ROC-AUC | 97.49% |
| TF-IDF Baseline Accuracy | 90.04% |
| Accuracy Improvement | +1.93 percentage points |

## Reliability Analysis

Validated confidence threshold:

**70%**

Results at the evaluated threshold:

- Coverage: 98.51%
- Accuracy: 92.51%
- Average confidence: 98.35%
- Correct-prediction average confidence: 98.87%
- Incorrect-prediction average confidence: 92.48%
- Confidence gap: 6.38 percentage points
- High-confidence errors: 307

The high-confidence errors demonstrate that confidence should not be
interpreted as a guarantee of correctness.

## Inference Architecture

Review Text
→ Streamlit
→ AutoTokenizer
→ DistilBERT
→ PyTorch Inference
→ Softmax Probabilities
→ Sentiment / Probability / Confidence

## Technology Stack

Python
- Natural Language Processing
- DistilBERT
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Streamlit
- Git
- GitHub

## Reproducibility and Release Engineering

The project was treated as an ML release rather than simply a notebook.

The public release contains 13 validated files and includes documentation,
results, usage instructions, requirements, release notes, reproducibility
evidence, and audit evidence.

Large trained-model artifacts were intentionally excluded from the public
repository through .gitignore protections.

Release validation included:

- SHA256 integrity verification
- Documentation validation
- Architecture consistency
- Claim governance
- Large-file protection
- Local/remote GitHub verification
- Final post-publication audit

## Professional Value

This project demonstrates the ability to build, benchmark, evaluate,
analyze reliability, package inference, document, release, and verify
an end-to-end NLP machine-learning system.

## GitHub

Repository:

Get-AZ/Level-4-Sentiment_Analysis_Project

Final published commit:

360f23fb2e1f65b154084269ff8c2bfc728b7906
