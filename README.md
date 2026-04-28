# Lost in Translation 🗺️

## A Mathematical Journey Through the Geometry of Meaning

> *"The limits of my language mean the limits of my world."*  
> — Ludwig Wittgenstein, *Tractatus Logico-Philosophicus*, 1921

---

## Overview

Monolingual word embeddings encode meaning as position in vector space. 
This project measures how much of that position survives translation.
Using monolingual fastText embeddings and multilingual LaBSE contextual 
embeddings, we define an experimental **Translation Loss metric ℒ(c)** and 
apply it to 30 carefully selected words across five languages: English, 
Spanish, Portuguese, Italian, and Bulgarian.

**Author:** Avgustina Daskalova  
**Institution:** SoftUni — Data Science Module  
**Submission:** Final Exam Project, April 2026

---

## Methods

| Method | Model | Type |
|--------|-------|------|
| Method 1 | fastText (monolingual) | Coordinate topology |
| Method 2 | Aligned fastText + RCSLS | Bridge (theoretical) |
| Method 3 | LaBSE | Semantic proximity |

---

## Data

Data files are not stored in this repository.  
📂 [Download from Google Drive](https://drive.google.com/drive/folders/1pCh3F9BommtSPDf40_lcGZbHGUV66XZj?usp=sharing)

Place CSV files in the same directory as the notebook before running.

---

## How to Reproduce

1. Clone this repository
2. Download data files from Google Drive link above
3. Place CSV files in the same directory as the notebook
4. Install dependencies (see below)
5. Run all cells top to bottom

> **Note:** fastText models (~6GB) are required only for Part A.  
> Skip to Part B using pre-extracted `vectors.csv` from Google Drive.

---

## Installation

```bash
pip install numpy pandas matplotlib seaborn gensim sentence-transformers scikit-learn scipy nltk
```

---

## License

See `LICENSES.md`
