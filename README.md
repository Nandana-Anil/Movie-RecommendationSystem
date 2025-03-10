﻿# Movie-RecommendationSystem

## 📌 Overview

This is a **Content-Based Movie Recommendation System** that suggests similar movies based on user input. It uses **Bag of Words (BoW)** and **Cosine Similarity** to find similar movies.

## 🚀 Features

- Uses **CountVectorizer** for text vectorization.
- Computes similarity using **Cosine Similarity**.
- Provides **top 5 movie recommendations** based on a selected movie.

## 🛠️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nandana-Anil/Movie-RecommendationSystem
cd MovieRecommendationSystem
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 📂 Dataset

Ensure your dataset (e.g., `movies.csv`) contains at least the following columns:

- **title**: Movie name
- **tags**: Combined text features (genres, description, actors, etc.)

## 🏗️ Usage

### **Run the Notebook**

1. Open **MovieRecommendationSystem.ipynb** in Jupyter Notebook.
2. Run all cells to preprocess the data and generate recommendations.
3. Input a movie title and get **top recommended movies**.

## 🤖 Technologies Used

- **Python**
- **Pandas**
- **Scikit-learn**
- **Numpy**

## 📜 License

This project is open-source and available under the **MIT License**.

