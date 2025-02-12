# 🎬 Movies Recommendation Project

## 🚀 Overview
This project utilizes **TF-IDF (Term Frequency-Inverse Document Frequency)** and **cosine similarity** to analyze and compare movie descriptions. By measuring textual similarity, the system recommends **five movies** with plots or themes that closely match the input movie.

## 🔥 Features
- **Content-Based Filtering:** Uses **TF-IDF** to transform movie descriptions into numerical vectors.
- **Cosine Similarity Calculation:** Identifies films with the most similar plots.
- **Efficient & Scalable:** Works well even with large movie datasets.
- **Easy to Use:** Input a movie title, and get five similar recommendations instantly!

## 🛠️ Tech Stack
- **Python** 🐍
- **Scikit-learn** 🤖 (for TF-IDF and similarity computation)
- **Pandas** 📊 (for data handling)
- **Numpy** 🔢 (for numerical operations)

## 📌 How It Works
1. **Preprocessing:** The dataset is cleaned, and movie descriptions are converted into TF-IDF vectors.
2. **Similarity Computation:** Cosine similarity is applied to measure textual similarity between movie descriptions.
3. **Recommendation System:** When a user selects a movie, the system finds and suggests five similar ones.


