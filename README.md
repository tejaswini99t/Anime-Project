# Anime-Project
Anime Recommendation System
This project presents an innovative anime recommendation system that employs machine learning techniques to suggest anime titles to users based on their preferences. Utilizing a content-based filtering approach, the system analyzes user-provided tags to recommend similar anime series or movies.
Dataset Used
The project leverages a comprehensive dataset from MyAnimeList, consisting of anime titles, genres, tags, and user ratings. The data spans various anime series and movies, enriched with metadata that includes directorial information, publication years, and user engagement metrics.
Dataset Used
The dataset foundational to the anime recommendation system was sourced from a comprehensive collection available on Kaggle (https://www.kaggle.com/datasets/alancmathew/anime-dataset/data). 

This dataset provided a rich variety of information, including titles, genres, descriptions, and viewer ratings, which are essential for building a content-based recommendation system.
Technology Stack
Python: The primary programming language for data processing and model development.
Scikit-learn: A machine learning library used for implementing the TF-IDF vectorizer and cosine similarity computations.
Pandas: For data manipulation and analysis.
SQLite: The chosen database for storing and querying the processed data.
Jupyter Notebooks: For interactive development and exploratory data analysis.
Data Model
The system employs a content-based filtering data model, utilizing a TF-IDF vectorization to convert textual data from anime tags and descriptions into a feature space. Cosine similarity measures provide the basis for calculating the likeness between anime titles, facilitating the recommendation process.
Data Flow
Data Collection: Gathering data from various sources and compiling it into a raw dataset.
Data Cleaning and Preparation: Normalizing, cleansing, and transforming data to prepare for analysis and modeling.
Feature Extraction: Using TF-IDF to transform text data into a weighted feature set.
Model Training: Applying cosine similarity to the TF-IDF vectors to train the model on the dataset.
Recommendation Generation: The system uses the trained model to predict and recommend anime titles based on a user's input tag.
User Interaction: Users interact with the system through a simple interface, receiving personalized anime recommendations.
