# Collaborative-filtering

This project implements a Product Recommendation System using Collaborative Filtering techniques powered by Apache Spark (PySpark). It aims to recommend personalized products to users based on their previous interactions and similarities with other users.

📊 Dataset
Source: Amazon Ratings Dataset on Kaggle
Size: ~1 million ratings



Attributes:
userId: Unique identifier for users
productId: Unique identifier for products
rating: Rating given by the user (1-5)
timestamp: Time when the rating was given 📦 Dataset used: Amazon Ratings on Kaggle


🚀 Technologies Used
PySpark (Apache Spark for Python)
ALS (Alternating Least Squares) Collaborative Filtering Algorithm
Jupyter Notebook
Pandas, Matplotlib for data analysis & visualization



🛠️ Key Features
Preprocessing of large-scale Amazon product rating data
Splitting data into training and testing sets
Building a recommendation model using PySpark's ALS algorithm
Evaluation using RMSE (Root Mean Square Error)
Generating top-N product recommendations for a user
