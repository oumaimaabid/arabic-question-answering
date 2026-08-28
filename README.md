# Arabic Question Answering — Research Project

This repository contains the cleaned and GitHub-ready version of my research notebook on **Arabic Question Answering (QA)**.

## Datasets

The project uses two Arabic QA datasets:

- **ARABICA**
- **ARCD (Arabic Reading Comprehension Dataset)**

The datasets are kept outside this repository to avoid unnecessary large files and to respect dataset distribution conditions. Please obtain them from their official/public sources and update the paths in the notebook.

## Approaches

The notebook compares several approaches for Arabic question answering, including:

- Generative QA
- Extractive QA
- Sentence-BERT (SBERT) based approach
- Hybrid approach

The experiments include models such as **DeepSeek-V3.1**, **BLOOM-560M**, and **RoBERTa SQuAD2**, as used in the original research notebook.

## Evaluation

The experiments evaluate the generated/extracted answers using:

- Exact Match (EM)
- F1 Score
- BLEU

Visualizations and result comparisons are also included.

## Project structure

```text
arabic-question-answering/
├── notebooks/
│   └── arabic_qa_github_ready.ipynb
├── results/
│   └── figures/
├── README.md
├── requirements.txt
├── .env.example
└── .gitignore
```

## Installation

Create a virtual environment and install the required Python packages:

```bash
pip install -r requirements.txt
```

If a Hugging Face model/API requires authentication, create an environment variable named `HF_TOKEN`.

Example:

```bash
HF_TOKEN=your_token_here
```

**Never commit your real token to GitHub.**

## Running the notebook

Open:

```text
notebooks/arabic_qa_github_ready.ipynb
```

and run the cells in order.

Before running the experiments, update the dataset paths according to where ARABICA and ARCD are stored locally.

## Reproducibility

The notebook is based on the original research work and has been cleaned for public GitHub publication. Some models may require substantial RAM/GPU resources.

## Author

**Oumaima Abidi**

Master's student/researcher in Information Systems and Web, with an interest in Data Science, Natural Language Processing and Machine Learning.
