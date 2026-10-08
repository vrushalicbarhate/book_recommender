# 📚 Book Recommendation System

A content-based book recommendation system that recommends books similar to a user's selected book using book metadata and similarity between books.

## 🚀 Overview

This project recommends books based on the similarity between their content and metadata.

The system processes information about books, converts the text into numerical representations using **TF-IDF**, and uses **cosine similarity** to find books that are most similar to the selected book.

It also includes a popular-books section to display highly rated and frequently interacted-with books.

## ✨ Features

- 📖 Search and select a book
- 🤖 Get recommendations for similar books
- 🔍 Content-based recommendation
- ⭐ Popular books section
- 📊 TF-IDF based text representation
- 📐 Cosine similarity for finding similar books
- 🌐 Streamlit-based interface

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Streamlit**
- **Pickle**

## 🧠 How It Works

The recommendation pipeline works in the following steps:

1. Book data is loaded and preprocessed.
2. Relevant book information is combined to create a content representation.
3. **TF-IDF Vectorization** converts the text information into numerical vectors.
4. **Cosine Similarity** calculates the similarity between books.
5. When a user selects a book, the system finds books with the highest similarity scores.
6. The most similar books are displayed as recommendations.

## 📂 Project Structure

```text
book_recommender/
│
├── PROJECT BOOKS.ipynb
├── Book_df.pkl
├── Book_pivot.pkl
├── popular.pkl
├── score.pkl
└── README.md
