# 🍽️ Restaurant Recommendation System - Cognifyz Internship Task

This project recommends similar restaurants based on user preferences using a **content-based filtering** approach. The model suggests restaurants similar to a selected one using text similarity (cuisine, city, price range).

---

## 🔍 Project Overview

- Dataset: Zomato Restaurant Data (9,500+ entries)
- Features used: `Cuisines`, `City`, `Price range`
- Model: TF-IDF Vectorization + Cosine Similarity
- Output: Top N similar restaurants for a given input

---

## 🛠️ Tech Stack

- Python
- Pandas, Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook

---

## ⚙️ How It Works

1. Preprocess the data (drop nulls, select important features)
2. Combine textual features into a single "tag"
3. Apply TF-IDF vectorization on tags
4. Compute cosine similarity between all restaurants
5. Recommend top 5 similar restaurants for a selected name

---

## ✅ Sample Output

Top 5 recommendations for Domino's Pizza:

Naivedya | Cuisines: North Indian | Rating: 3.4

Bhoj Restaurant | Cuisines: North Indian | Rating: 3.7

Kareem's Kabab & Biryani | Cuisines: Mughlai | Rating: 3.4

Angeethi Restaurant | Cuisines: North Indian, Chinese | Rating: 3.3

Great Sagar Restaurant | Cuisines: North Indian, Mughlai | Rating: 3.3
