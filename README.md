🎬 Movie Success Rate Prediction using Decision Tree
📌 Overview

This project predicts the success rate of movies using a Decision Tree Machine Learning model. The model analyzes various factors such as budget, genre, cast popularity, and ratings to determine whether a movie is likely to be successful.

The goal is to help understand what factors contribute most to a movie’s success.

🚀 Features

Data preprocessing and cleaning

Handling categorical and numerical features

Decision Tree model training

Feature importance analysis

Model evaluation and visualization

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

📂 Dataset

The dataset includes the following features:

🎭 Genre

💰 Budget

⭐ Cast Popularity

🎬 Director Reputation

📊 IMDb Rating

📅 Release Year

🎟️ Box Office Collection (Target / Success Label)

(Update based on your actual dataset)

🌳 Model Explanation

The Decision Tree algorithm splits the dataset based on feature values to predict movie success.

It uses criteria like Gini Index to decide the best split:

𝐺
𝑖
𝑛
𝑖
=
1
−
∑
(
𝑝
𝑖
)
2
Gini=1−∑(p
i
	​

)
2

Where:

𝑝
𝑖
p
i
	​

 = probability of each class
