# 🎬 Movie Recommendation System

A content-based movie recommendation system built with **Python**, **NLTK**, and **Cosine Similarity**. Movie metadata is preprocessed, transformed into feature vectors, and a cosine similarity matrix is computed once and stored in `similarity.pkl` for fast recommendations at runtime.

### 🚀 Live Demo
[Try it here](https://movie-recommendation-system-crc4usvekmyrhfwujwymxn.streamlit.app/) 

## Features

- Content-based movie recommendations
- Text preprocessing using NLTK
- Precomputed cosine similarity matrix for faster inference
- Streamlit-based interactive interface

## Project Structure

```text
.
├── app.py
├── movies.pkl
├── similarity.pkl
└── README.md
```

## Run Locally

```bash
streamlit run app.py
```
