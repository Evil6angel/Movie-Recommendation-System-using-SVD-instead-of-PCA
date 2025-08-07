# Movie Recommendation System using SVD

This project modifies a class-studied recommendation system to use **Singular Value Decomposition (SVD)** instead of **Principal Component Analysis (PCA)**, applying it to a **movie ratings dataset** to generate personalized recommendations.  

The system leverages matrix factorization to uncover latent user-item features and predict ratings for unseen movies.

---

## Objectives
- Replace PCA with **SVD** for dimensionality reduction in the recommendation engine.
- Apply the new approach to a **movie ratings dataset**.
- Evaluate model performance and visualize recommendation patterns.
- Compare original and modified systems.

---

## Dataset
- **Source:** [MovieLens dataset or custom]  
- **Description:** User–movie ratings matrix with user IDs, movie IDs, and rating scores.
- **Size:** [Number of users, movies, and ratings].
- **Format:** CSV / DataFrame.

---

## Methodology
1. **Data Preprocessing**
   - Load and clean movie ratings data.
   - Create user–item rating matrix.
   - Handle missing values and normalize ratings.

2. **Model Development**
   - Apply **SVD** for latent factor extraction.
   - Reconstruct predicted ratings matrix.
   - Generate **Top-N recommendations** for each user.

3. **Evaluation**
   - Compare predicted vs. actual ratings (RMSE, MAE).
   - Visualize rating distribution and recommendation coverage.

4. **Visualization**
   - Bar plots of top recommended movies.
   - Heatmaps of predicted ratings.
   - Latent feature scatter plots.

---

## 🛠Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook

---
