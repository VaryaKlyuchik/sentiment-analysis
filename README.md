# IMDb Review Sentiment Classification

## Project Overview

This project implements a complete Natural Language Processing (NLP) pipeline for binary sentiment classification of movie reviews from the IMDb dataset.

The main objective is to build a machine learning model that predicts whether a review expresses a **positive** or **negative** sentiment. The project covers all stages of a classical NLP workflow, including data exploration, text preprocessing, feature extraction using TF-IDF, model training, and performance evaluation.

---

## Dataset

- **Dataset:** IMDb Movie Reviews
- **Source:** https://ai.stanford.edu/~amaas/data/sentiment/
- **Size:** 50,000 labeled movie reviews
- **Classes:** Positive / Negative

The dataset is balanced, making it suitable for binary text classification tasks.

---

## Technologies

- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Jupyter Notebook
- Git

---

## Machine Learning Pipeline

The project consists of the following stages:

1. Data loading
2. Exploratory Data Analysis (EDA)
3. Text cleaning and preprocessing
4. TF-IDF vectorization
5. Train/Test split
6. Logistic Regression model training
7. Model evaluation
8. Error analysis
9. Conclusions

---

## Results

| Metric | Score |
|--------|------:|
| Accuracy | - |
| Precision | - |
| Recall | - |
| F1-score | - |

> The metrics will be updated after the model is trained.

---

## Repository Structure

```
sentiment-analysis/
│
├── README.md
├── sentiment_analysis.ipynb
├── requirements.txt
├── .gitignore
└── data/
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/sentiment-analysis.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```
sentiment_analysis.ipynb
```

Run all cells from top to bottom.

---

## Possible Improvements

- Compare Logistic Regression with other classical machine learning models.
- Tune TF-IDF parameters.
- Perform hyperparameter optimization.
- Experiment with transformer-based language models such as BERT.
- Analyze model errors in greater detail.

---

## Author

**Barbara Klyucheva**

Student at Lomonosov Moscow State University

Interested in Machine Learning, Natural Language Processing and Large Language Models.
