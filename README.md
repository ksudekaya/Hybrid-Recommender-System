# Hybrid-Recommender-System
This project builds a hybrid recommendation system using collaborative filtering techniques to recommend movies to a user. The system combines user-based and item-based recommendation approaches to provide personalized movie suggestions.

Table of Contents
Project Overview
Dataset
Getting Started
Methodology
Data Preparation
User-Based Recommendations
Item-Based Recommendations
Hybrid Recommendations
Installation
Usage
Contributing
License
Project Overview
This hybrid recommender system utilizes collaborative filtering to generate movie recommendations based on user preferences and movie similarity. For each user, the system suggests 5 movies through a user-based collaborative filtering model and 5 movies through an item-based collaborative filtering model.

The main objectives:

Use collaborative filtering to recommend movies based on users' past ratings.
Provide both user-based and item-based recommendations to optimize accuracy.

#Dataset
The project uses two primary datasets:

Movie Dataset - Contains movie IDs, titles, and genres.
Rating Dataset - Includes user IDs, movie IDs, ratings, and timestamps.
These datasets are required for merging to generate meaningful recommendations. Both datasets can be accessed on Kaggle or other movie rating databases.
