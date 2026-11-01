# Natural Language Processing (NLP) Projects

A collection of Python notebooks exploring Natural Language Processing and text-based sentiment analysis. The projects demonstrate text tokenization, lemmatization, sentiment scoring, and basic text mining workflows using NLTK, VADER, TextBlob, Pandas, and Scikit-learn.

## Projects

| Project | Tools / Techniques | Description |
|---|---|---|
| NLTK Fundamentals | NLTK, tokenization, lemmatization, VADER | Explores sentence and word tokenization, word lemmatization, and sentiment analysis on user input. |
| Twitter Comment Sentiment Analysis | NLTK VADER, Pandas | Calculates sentiment scores and positive, negative, or neutral labels for Twitter comments. |
| Twitter Post Text Mining | TextBlob, Pandas, Scikit-learn, Random Forest | Analyzes post descriptions, derives sentiment polarity, and explores ML-based prediction. |

## Technologies & Tools

- **Programming Language:** Python
- **NLP:** NLTK, TextBlob
- **Sentiment Analysis:** VADER SentimentIntensityAnalyzer, TextBlob Polarity
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Development Environments:** Jupyter Notebook, Google Colab

## Concepts Covered

- Text tokenization
- Sentence tokenization
- Word lemmatization
- Sentiment polarity and compound scores
- Positive, negative, and neutral sentiment classification
- Text preprocessing and missing-value handling
- Basic text mining
- Model training and evaluation concepts

## Repository Structure

```text
NLP-Projects/
├── NLTK-Fundamentals/
│   └── nltk_fundamentals.ipynb
├── Twitter-Comment-Sentiment/
│   └── twitter_comment_sentiment_nltk.ipynb
├── Twitter-Post-Text-Mining/
│   └── twitter_post_text_mining_ml.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/NLP-Projects.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebooks using Jupyter Notebook, JupyterLab, or Google Colab.

## Dataset Information

The Twitter analysis notebooks require external datasets that are not included in this repository:

- `twitter_dataset.csv` — required by the Twitter comment sentiment notebook.
- `twitter-posts.csv` — required by the Twitter post text-mining notebook.

Place each CSV file in the notebook's working directory before running the corresponding notebook. The NLTK fundamentals notebook accepts text directly from user input and does not require a dataset.

NLTK may download required resources on first execution, including `punkt_tab`, `wordnet`, and `vader_lexicon`.

## Notes

These notebooks are learning and portfolio projects. Sentiment scores are generated using lexicon-based tools and should not be treated as verified human sentiment labels. The Twitter post notebook retains its original ML experiments; its metrics require a proper train/test evaluation before being interpreted as generalization performance.

## Author

**Ahamed Refai S**

Computer Science Graduate | Python Developer | AI & Machine Learning | Data Science | Backend Development

- **GitHub:** https://github.com/YOUR-USERNAME
- **LinkedIn:** https://www.linkedin.com/in/ahamed-refai-s-6775b2310

---

*Exploring language, sentiment, and text intelligence with Python.*
