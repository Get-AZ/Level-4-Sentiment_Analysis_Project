# Project Structure

```text
Sentiment_Analysis_Project/
│
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
│
├── transformer/
│   ├── models/
│   │   ├── distilbert_baseline/
│   │   ├── distilbert_finetuned_best/
│   │   ├── distilbert_finetuned_final/
│   │   └── tokenizer/
│   │
│   ├── outputs/
│   ├── figures/
│   ├── deployment/
│   │
│   └── final_release/
│       ├── model/
│       ├── best_model/
│       ├── tokenizer/
│       ├── application/
│       ├── docs/
│       ├── reports/
│       └── integrity/
│
└── github_release/
    ├── README.md
    ├── LICENSE
    ├── .gitignore
    ├── requirements.txt
    ├── docs/
    └── reports/
```

## Important Directories

### models/

Contains the trained DistilBERT model variants and tokenizer artifacts.

### final_release/

Contains the validated production release package.

### outputs/

Contains project reports, validation outputs, and analysis artifacts.

### figures/

Contains project visualizations.

### deployment/

Contains deployment-related project resources.

### github_release/

Contains GitHub-ready documentation and repository metadata.
