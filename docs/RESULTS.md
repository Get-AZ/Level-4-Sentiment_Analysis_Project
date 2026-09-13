# Final Model Results

## DistilBERT Performance

| Metric | Score |
|---|---:|
| Accuracy | 91.97% |
| Precision | 91.90% |
| Recall | 92.12% |
| F1 Score | 92.01% |
| ROC-AUC | 97.49% |

## Baseline Comparison

| Metric | TF-IDF | DistilBERT | Gain |
|---|---:|---:|---:|
| Accuracy | 90.04% | 91.97% | +1.93 pp |
| Precision | 89.32% | 91.90% | +2.58 pp |
| Recall | 90.96% | 92.12% | +1.16 pp |
| F1 | 90.13% | 92.01% | +1.88 pp |
| ROC-AUC | 96.50% | 97.49% | +0.99 pp |

## Reliability

- Average confidence: 98.35%
- Correct average confidence: 98.87%
- Incorrect average confidence: 92.48%
- Confidence gap: 6.38 pp
- Low-confidence records: 74
- High-confidence errors: 307
- Recommended threshold: 70%
- Coverage at threshold: 98.51%
- Accuracy at threshold: 92.51%

## Conclusion

DistilBERT produced the strongest overall performance and improved
upon the classical TF-IDF baseline on every tracked metric.

The final model is therefore selected as the production sentiment
classifier.
