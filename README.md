# 🔍 Personalized Yelp Rating Prediction using LSH and Hybrid Recommendation Systems

This repository contains code for building a hybrid recommendation system using PySpark RDDs and XGBoost. The project is part of the DSCI 553: Foundations and Applications of Data Mining course, and leverages a subset of the Yelp dataset to generate personalized predictions and identify similar businesses.

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
- Data
- Output
- Recommendation_system.ipynb

