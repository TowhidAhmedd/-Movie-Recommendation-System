#  Movie Recommendation System (NLP-Based)

A content-based movie recommendation system built using **Natural Language Processing (NLP)** and **Machine Learning**.  
The system recommends similar movies based on movie description, genres, keywords, cast, and crew.

---

## Project Overview

This project uses NLP techniques to understand movie content and recommend similar movies based on user input.  
It analyzes textual features like **overview, tags, genres** and converts them into numerical vectors for similarity calculation.

---

## Features

- Content-based movie recommendation
- NLP-based text processing
- Similarity calculation using cosine similarity
- Fast and accurate recommendations
- Dataset preprocessing and feature engineering

---

## Tech Stack

- Python 
- Pandas
- NumPy
- Scikit-learn
- NLP (NLTK / Text Processing / Tf-idf)
- Streamlit

---

## Dataset

- Movie dataset containing:
  - Title
  - Overview
  - Genres
  - Keywords
  - Cast & Crew

---

## How It Works

1. Data Cleaning & Preprocessing
2. Combine important text features (tags)
3. Convert text into vectors using NLP techniques
4. Compute similarity matrix
5. Recommend top similar movies

---

## NLP Techniques Used

- Text Cleaning
- Tokenization
- Stemming
- Bag of Words / Count Vectorizer or TF-IDF
- Cosine Similarity

---

## Installation


git clone https://github.com/TowhidAhmedd/Movie-Recommendation-System.git  
cd Movie-Recommendation-System 
pip install -r requirements.txt  
