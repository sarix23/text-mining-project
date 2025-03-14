
# 🎥 **Exploring Genre Similarities & Enhancing Movie Recommendations with Clustering & Topic Modeling**  

![Movie Dataset Overview](https://pbs.twimg.com/profile_images/1243623122089041920/gVZIvphd_400x400.jpg)  

---

## 📌 **Table of Contents**  
1. [🎬 Dataset Description](#dataset-description)  
2. [🎯 Project Goals](#project-goals)  
   - [📊 Clustering](#1-clustering)  
   - [🧠 Topic Modeling](#2-topic-modeling)  
3. [📂 How to Use the Dataset](#how-to-use-the-dataset)  
   - [⬇️ Download Data](#download-data)  
4. [🛠️ Required Libraries](#required-libraries-python)  
5. [📜 License](#license)  
6. [📧 Contact](#contact)  

---

## 🎬 **Dataset Description**  

The **TMDb** (The Movie Database) is a vast and **daily updated** movie dataset that provides details such as **titles, ratings, release dates, revenue, genres**, and much more! 🍿  

📌 This dataset contains over **1.4M movies** and is suitable for exploring **genre patterns, recommendation systems, and movie analytics**.  

🔗 [Check it out on Kaggle!](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data)  

---

## 🎯 **Project Goals**  

### 1️⃣ **Clustering** 📊  
This section applies **clustering algorithms** to identify **genre similarities** between movies. Techniques used include:  
- 🔹 *k-means*  
- 🔹 *hierarchical clustering*  
- 🔹 *fuzzy c-means*  

The goal is to **group movies based on genre-related patterns**, revealing relationships that may not be evident in traditional classifications.  

### 2️⃣ **Topic Modeling** 🧠  
A **movie recommendation system** is developed by analyzing **overview texts** and applying **topic modeling**.  

📝 Keywords extracted from movie descriptions are used to enhance **cosine similarity scores**, grouping movies by thematic content rather than just textual similarity.  

📊 A comparison is conducted between **topic-based recommendations** and **traditional text similarity approaches** to assess the effectiveness of thematic modeling.  

---

## 📂 **How to Use the Dataset**  

### ⬇️ **Download Data**  
The version used in this analysis is dated **January 4, 2025**.  

📢 **For the latest version**, download it directly from Kaggle:  
🔗 [Get the dataset here!](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data)  

⚠️ *Follow the notebook guidelines for proper data retrieval!*  

---

## 🛠️ **Required Libraries (Python)**  

The following libraries are required for this project:  

📌 **Data Processing & ML**  
✔️ `pandas` – Data manipulation  
✔️ `numpy` – Numerical operations  
✔️ `sklearn` – Machine learning & clustering  
✔️ `scipy` – Scientific computations  

📌 **Text Analysis & NLP**  
✔️ `spacy` – Natural Language Processing  
✔️ `gensim` – Topic modeling (LDA, CoherenceModel)  
✔️ `sentence-transformers` – Sentence embeddings  

📌 **Visualization & Analysis**  
✔️ `matplotlib` & `seaborn` – Data visualization 📊  
✔️ `networkx` – Graph-based analysis 🌐  
✔️ `wordcloud` – Generate word clouds ☁️  

📌 **Others**  
✔️ `skfuzzy` – Fuzzy clustering 🤖  
✔️ `re` – Regular expressions for text cleaning  
✔️ `kneed` – Finding the "elbow point" for clustering  

💡 *If `skfuzzy` installation issues arise, try:*  
```bash
pip install -U scikit-fuzzy
```

## **📜License**:
📝 MIT License – Free to use, modify, and distribute.

---

## **👩🏽‍💻Contact**
For any questions, contact via email at:
- Francesca Del Giudice [f.delgiudice3@campus.unimib.it].
- Sara Nava [s.nava38@campus.unimib.it]
- Giulia Saresini [g.saresini@campus.unimib.it]

