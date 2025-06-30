# Movie-Recommendation-System-Using-Apache-Spark---Big-Data

This project is a **Big Data-based Movie Recommendation System** built using **Apache Spark** and **PySpark**. It leverages the **Alternating Least Squares (ALS)** algorithm from **Spark MLlib** to generate personalized movie recommendations based on collaborative filtering.

---

## 📌 Project Overview

- ⚡ Built a scalable and fault-tolerant recommendation engine capable of processing **100,000+ ratings** from the MovieLens dataset.
- 🔁 Implemented **Collaborative Filtering** using the **ALS algorithm** to predict user preferences.
- 🧠 Focused on building an **end-to-end big data pipeline** that includes:
  - Data preprocessing and transformation
  - Model training and evaluation
  - Real-time performance optimization using distributed computing

---

## 🚀 Tech Stack

| Category            | Tools & Frameworks                     |
|---------------------|----------------------------------------|
| Language            | Python                                 |
| Big Data Engine     | Apache Spark                           |
| API                 | PySpark (RDD, DataFrame)               |
| ML Algorithm        | ALS (Alternating Least Squares)        |
| Dataset             | MovieLens                              |
| Evaluation Metric   | RMSE (Root Mean Square Error)          |
| Storage             | HDFS                                   |
| Version Control     | Git, GitHub                            |

---

## 📂 Dataset

- **MovieLens 100k** dataset  
- Contains user ratings on various movies  
- Download link: [https://grouplens.org/datasets/movielens/](https://grouplens.org/datasets/movielens/)

---

## 🔧 Features

- 📊 Personalized movie recommendations using matrix factorization
- 🔁 Support for large-scale, distributed data processing
- ⚙️ Fault-tolerant architecture using HDFS + Spark
- 🧪 Evaluation using RMSE for model accuracy

---

## 📈 Model Workflow

1. Load MovieLens data from HDFS
2. Preprocess and clean the dataset
3. Split data into training and testing sets
4. Train ALS model using Spark MLlib
5. Predict ratings and evaluate using RMSE
6. Recommend top N movies to each user

---

## 🖥️ How to Run the Project

### Prerequisites:
- Apache Spark
- Python 3.x
- PySpark
- Hadoop (HDFS configured)

### Run the Code:
```bash
# Clone the repository
git clone https://github.com/your-username/movie-recommendation-spark.git
cd movie-recommendation-spark

# Submit PySpark script
spark-submit movie_recommendation.py
