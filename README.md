# 🎬 Task 3: Movie Recommendation System

An intermediate-level Machine Learning project built during my internship at **VedGrow**. This project implements a collaborative filtering recommendation engine using the popular **MovieLens 100K dataset** to predict user movie ratings and generate personalized movie suggestions.

---

## 🏢 Project Overview
The primary objective of this project is to build an engine that analyzes historical user rating patterns and accurately predicts how a specific user would rate unseen movies. The model leverages matrix factorization to uncover latent features capturing user preferences and item characteristics.

### 🚀 Key Features Implemented:
* 📥 **Automated Data Fetching:** Utilized the Surprise library's built-in robust data pipelines to load and manage the MovieLens 100K ratings dataset dynamically.
* 🤖 **Collaborative Filtering Engine:** Implemented Matrix Factorization logic using the **SVD (Singular Value Decomposition)** algorithm.
* 📈 **System Evaluation Matrix:** Rigorously calculated ranking relevance using industry-standard verification loops via **Precision@K** and **Recall@K** metrics.
* 📊 **Data Visualizations:** Generated separate standalone analytic bar charts analyzing personalized recommendation distributions and validation accuracy score baselines.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Core Frameworks:** Scikit-Surprise (SVD optimization layer)
* **Data Processing:** Pandas, NumPy
* **Visualization Engine:** Matplotlib, Seaborn

---

## 📊 Performance Metrics (At K=10)
After training the SVD algorithm model framework on historical user rating splits, the following validation thresholds were achieved:
* 🔹 **Precision @ 10:** ~78.5% (Proportion of recommended movies that were highly relevant)
* 🔹 **Recall @ 10:** ~43.2% (Proportion of total relevant movies captured in Top-10 lists)

---

## 📂 Project Architecture
```text
📂 movie_recommendation_system/
├── 📄 movie_recommender.ipynb      # Main Jupyter Notebook with code splits
├── 📄 chart_1_recommendations.png   # Generated recommendations visualization plot
└── 📄 chart_2_metrics.png           # Generated precision/recall baseline plot
```

---

## ⚙️ How to Run the Project
1. Open the project repository directory inside your local environment terminals.
2. Install the necessary baseline dependencies matching current kernel parameters:
   ```bash
   pip install pandas numpy scikit-learn scikit-surprise matplotlib seaborn
   ```
3. Open **VS Code**, select your active Python kernel, and execute the structural code cells sequentially from `Cell 1` through `Cell 6` inside the `movie_recommender.ipynb` notebook file.

---

## 👤 Author
* **MYLA DIVYA SAI SRI** 

