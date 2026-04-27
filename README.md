# Lost in Translation

# A Mathematical Journey Through the Geometry of Meaning

# Author: Avgustina Daskalova

# Institution: SoftUni — Data Science Module

# Submission: Final Exam Project, April 2026

# 

# Project Overview

# Can we measure how much meaning is lost in translation? This project designs a computational experiment to quantify semantic translation loss across five languages — English, Spanish, Portuguese, Italian and Bulgarian — using word embeddings, cosine similarity, and an original experimental application of cosine distance as a Translation Loss metric ℒ(c).

# 

# Repository Structure

# Lost-in-Translation/

# ├── Lost\_In\_Translation.ipynb

# ├── README.md

# ├── .gitignore

# └── models/

# 

# Data Files

# Data files are hosted on Google Drive (not committed to this repository per academic best practices):

# https://drive.google.com/drive/folders/1pCh3F9BommtSPDf40\_lcGZbHGUV66XZj?usp=sharing

# word\_list.csv — 30 concepts x 5 languages, author-curated

# vectors.csv — Pre-extracted fastText vectors (328 KB)

# translation\_loss\_method1.csv — Method 1 results

# translation\_loss\_method3.csv — Method 3 LaBSE results

# 

# Methods

# Method 1 — Monolingual fastText — Meta AI Common Crawl vectors — Complete

# Method 2 — Aligned fastText RCSLS — Aligned cross-lingual vectors — Theory only

# Method 3 — LaBSE — Google multilingual BERT — Complete

# 

# Key Finding

# Method 1 measured coordinate distance, not semantic distance. LaBSE, by projecting all languages into a single shared space, reveals the meaning that was always there.

# saudade (longing\_EN to saudade\_PT):

# fastText: cosine similarity = 0.037

# LaBSE: cosine similarity = 0.791

# 

# Requirements

# Python 3.10+

# numpy, pandas, matplotlib, seaborn

# gensim, sentence-transformers

# scikit-learn, scipy, nltk

# Install: pip install numpy pandas matplotlib seaborn gensim sentence-transformers scikit-learn scipy nltk

# 

# How to Reproduce

# 

# Clone this repository

# Download data files from Google Drive link above

# Place CSV files in the same directory as the notebook

# Run all cells top to bottom

# fastText models (6GB) required only for Part A — skip to Part B using pre-extracted vectors.csv

# 

# 

# Academic Integrity

# All Bulgarian translations provided by the author as a native speaker.

# AI coding assistance: Claude Sonnet (Anthropic, 2025-2026).

# All code reviewed, tested and validated by the author.

# Sources documented in Section 10 — The Compass.

# 

