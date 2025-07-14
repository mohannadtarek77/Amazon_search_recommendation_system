# Amazon_search_recommendation_system
Here’s a GitHub repo description you can use, summarizing the project based on your images and your notes:

---

## 📦 Amazon Software Recommendation System

This project is a **Neural Collaborative Filtering-based recommendation system** trained on the **UCSD Amazon Software Reviews dataset** (592K+ reviews). It is built using **Google Colab**, making it easy to run and modify, especially for beginners in **AI**, **Deep Learning (DL)**, and **Natural Language Processing (NLP)**.

### 🚀 Highlights

* **Framework**: Implemented in Google Colab using modular, beginner-friendly code blocks.
* **Goal**: Recommend software based on user preferences, engagement, and review behavior.
* **Dataset**:

  * Source: UCSD Amazon Software Reviews (McAuley Lab)
  * Features: `rating`, `user_id`, `item_id`, `timestamp`
  * Filtered users with ≥10 reviews and items with ≥5 reviews
  * Chronological split (Train/Val/Test: 70/15/15) with unseen samples removed

### 🧠 Model Features

* **Explicit Feedback**: Star ratings (1–5 scale)
* **Implicit Feedback**: Review length, helpfulness votes
* **Temporal Features**: Review recency and time since purchase
* **Textual Features**: Sentiment scores extracted using NLP

### 🏗️ Architecture

A multi-layer feedforward neural network that takes user and item embeddings, processes them through dense layers with ReLU activations and dropout, and outputs a predicted rating.

---

Let me know if you'd like to include Colab links, installation instructions, or performance metrics!

