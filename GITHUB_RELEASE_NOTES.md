# Release v1.0.0 — DistilBERT Production Release

## Release Status

**Production Ready**

## Highlights

- DistilBERT selected as final production model
- 91.97% test accuracy
- 92.01% F1 score
- 97.49% ROC-AUC
- +1.93 percentage-point accuracy gain over TF-IDF
- Confidence threshold validated at 70%
- 98.51% coverage at recommended threshold
- Streamlit deployment validated
- Reproducibility artifacts validated
- SHA256 integrity artifacts generated

## Validation

Final project validation passed.

## Deployment

The application can be launched using:

```bash
streamlit run app.py
```

## Model Files

Large model files are excluded from GitHub through `.gitignore`.

The validated production release package remains available separately.

## Project Context

This release contains the final DistilBERT Transformer model for binary sentiment analysis of movie reviews. The project evaluates NLP text-classification performance and compares the Transformer approach against a TF-IDF baseline.
