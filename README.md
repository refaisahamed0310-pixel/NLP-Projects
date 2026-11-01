# NLP Projects

A collection of practical **Natural Language Processing (NLP)** projects built with Python. This repository demonstrates core text-processing techniques, sentiment analysis, and machine-learning workflows using popular NLP and data-science libraries.

## Projects

| Project | Description | Key Technologies |
|---|---|---|
| **NLTK Fundamentals** | Demonstrates sentence and word tokenization, lemmatization, and rule-based sentiment analysis using VADER. | NLTK, VADER |
| **Twitter Comment Sentiment Analysis** | Analyzes the sentiment of Twitter-style comments and exports the results to a CSV file. | NLTK, VADER, Pandas |
| **Twitter Post Text Mining** | Explores text-based features, sentiment labeling, and machine-learning experiments on post descriptions. | TextBlob, Pandas, Scikit-learn |

## Repository Structure

```text
NLP-Projects/
├── NLTK-Fundamentals/
│   └── nltk_fundamentals.ipynb
├── Twitter-Comment-Sentiment/
│   └── twitter_comment_sentiment_nltk.ipynb
├── Twitter-Post-Text-Mining/
│   └── twitter_post_text_mining_ml.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Tech Stack

- **Language:** Python
- **NLP:** NLTK, TextBlob
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Development:** Jupyter Notebook

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/refaisahamed0310-pixel/NLP-Projects.git
cd NLP-Projects
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS / Linux:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook for the project you want to explore and follow its cells in order.

## Dataset Notes

Some notebooks expect input datasets to be available locally. Place each dataset in the location specified in the relevant notebook, or update the dataset path to match your local setup. Datasets are not included unless explicitly provided in the repository.

## Important Notes

- These notebooks are learning and portfolio projects, not production-ready NLP systems.
- Results depend on the dataset, preprocessing choices, and model configuration.
- Sentiment labels produced by lexicon-based tools are estimates and should not be treated as definitive interpretations.
- The Twitter post text-mining notebook includes exploratory machine-learning experiments. Its evaluation approach has limitations, including evaluation on training data; reported scores should not be interpreted as reliable estimates of performance on unseen data.
- Review dataset sources and usage terms before redistributing any data.

## Author

**Ahamed Refai S.**  
Computer Science Graduate | Python Developer | AI & Machine Learning | Data Science

- GitHub: [refaisahamed0310-pixel](https://github.com/refaisahamed0310-pixel)
- LinkedIn: [Ahamed Refai](https://www.linkedin.com/in/ahamed-refai-s-6775b2310/)

---

If you find this repository useful, feel free to star it.
