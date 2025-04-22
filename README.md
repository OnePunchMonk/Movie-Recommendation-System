# Movie-Recommendation-System

This project builds a movie recommendation system using Apache Spark's MLlib and the MovieLens dataset. It leverages the **Alternating Least Squares (ALS)** algorithm for collaborative filtering to predict user preferences and recommend movies accordingly.

## 📁 Dataset

- **Source**: [MovieLens](https://grouplens.org/datasets/movielens/)
- Includes user ratings for movies, along with movie metadata.

## ⚙️ Technologies Used

- PySpark
- ALS (Alternating Least Squares) Model
- MovieLens Dataset
- Jupyter Notebook / Python Scripts

## 🧠 Model

The ALS algorithm is used to train a collaborative filtering model on user-item interactions. It predicts missing entries in the user-item matrix to provide personalized movie recommendations.

## 📉 Evaluation

- Train/Test split for model validation
- RMSE (Root Mean Square Error) used to evaluate prediction accuracy

## 🚫 Shortcomings

- Cold-start problem: The model cannot effectively recommend for new users or new items without prior interaction data.

## 🚀 Future Extensions

- Combine with content-based filtering to handle the cold-start problem more effectively.
- Deploy the model using Flask/Django for real-time recommendations.
- Add evaluation metrics like Precision@K or Recall@K for better performance analysis.

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-pyspark.git
   cd movie-recommendation-pyspark

2. Install pyspark and run
   ```bash
   pip install pyspark
   pyspark main.py   
