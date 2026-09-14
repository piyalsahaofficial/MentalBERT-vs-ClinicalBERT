# MentalBERT vs ClinicalBERT

## Overview

A comparative study of **MentalBERT** and **ClinicalBERT** for sentiment analysis of mental-health-related text using transformer-based language models.

This project contains the experimental implementation and evaluation conducted as part of an **IEEE-published research paper**.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- Jupyter Notebook
- Google Colab

## Dataset

**Sentiment Analysis for Mental Health** dataset from Kaggle.

[View Dataset](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health)

## Results

| Metric | MentalBERT | ClinicalBERT |
|---|---:|---:|
| Precision | **80.38%** | 77.52% |
| Recall | **81.39%** | 78.33% |
| Accuracy | **83.54%** | 81.58% |
| F1-Score | **80.74%** | 77.58% |

**MentalBERT outperformed ClinicalBERT across all four evaluation metrics.**

## Research Paper

**MentalBERT: A Comparative Study on Addressing Mental Health Issues Using Transformer-Based Language Model**

- **Publisher:** IEEE
- **Status:** Published
- **Authors:** Piyal Saha *et al.*
- **DOI:** [10.1109/FET68771.2026.11601738](https://doi.org/10.1109/FET68771.2026.11601738)
- **IEEE Xplore:** [View Paper](https://ieeexplore.ieee.org/document/11601738)

## Repository Structure

```text
MentalBERT-vs-ClinicalBERT/
│
├── notebooks/
│   └── experiments.ipynb
│
├── results/
│   ├── metrics/
│   └── plots/
│
├── requirements.txt
└── README.md
```

## How to Run

```bash
pip install -r requirements.txt
```

Open `notebooks/experiments.ipynb` in Google Colab or Jupyter Notebook and run the cells sequentially.

## Author

Piyal Saha  
[GitHub Profile](https://github.com/piyalsahaofficial)
