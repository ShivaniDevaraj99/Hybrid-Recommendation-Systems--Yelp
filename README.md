# 🔍 Personalized Yelp Rating Prediction using LSH and Hybrid Recommendation Systems

This repository contains the implementation of a hybrid recommendation system that combines collaborative filtering (CF), model-based learning (XGBoost), and Locality Sensitive Hashing (LSH) using PySpark RDDs. The system is designed to generate personalized user-business rating predictions and identify similar businesses based on user interaction patterns.

The project works with a preprocessed subset of the Yelp dataset, where user reviews, business ratings, and metadata are used to build scalable, efficient, and accurate recommender models.

---

## 🧠 Project Overview

The system is designed to tackle core problems in large-scale recommender systems by integrating:

- 🧮 **Locality Sensitive Hashing (LSH)** for efficient similarity detection  
- 🧊 **Collaborative Filtering (CF)** using Pearson similarity  
- 🧠 **Model-based prediction** using metadata features with XGBoost  
- 🔗 **Hybrid approach** that smartly blends CF and model-based results for robust predictions

---

## 🧪 Methodology

- **Data Source**: Filtered subset of the Yelp Review Dataset (CSV format)  
- **Tech Stack**: `PySpark RDD`, `Python`, `XGBoost`  
- **Approaches**:
  - LSH with Jaccard similarity to detect similar businesses (Task 1)
  - Item-based CF using Pearson correlation (Task 2 Case 1)
  - Model-based predictions using XGBoost and business/user features (Task 2 Case 2)
  - Hybrid system with a weighted average strategy (Task 2 Case 3)

---

## 📂 File Structure
- output_final.csv
- Recommendation_system.ipynb

