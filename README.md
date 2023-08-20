
# Recipe Recommendation and Classification System

This repository contains code for a Recipe Recommendation and Classification System. The system uses Natural Language Processing (NLP) techniques to analyze and recommend recipes based on their ingredients. Additionally, it includes text classification models to predict the course category of a recipe (e.g., Main Course, Dessert, Starter, Snack, Beverage) based on its ingredients.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Dependencies](#dependencies)

## Introduction

This project aims to provide two main functionalities:
1. **Recipe Recommendation**: The system uses TF-IDF vectorization and KMeans clustering to group recipes based on their ingredients. Given a recipe, the system recommends similar recipes from the same cluster.

2. **Course Classification**: The system includes text classification models (Logistic Regression, Support Vector Machine, Random Forest) to predict the course category of a recipe (e.g., Main Course, Dessert, Starter, Snack, Beverage) based on its ingredients.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/recipe-recommendation-classification.git
   ```

2. Navigate to the project directory:
   ```
   cd recipe-recommendation-classification
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. **Recipe Recommendation**:
   - Run the `recipe_recommendation.py` script to load and preprocess the data, perform clustering, and create recommendations based on recipe titles.
   - Use the function `recommend_recipes_content_based` in the script to recommend similar recipes based on a given recipe title.

2. **Course Classification**:
   - Run the `course_classification.py` script to load and preprocess the data, train classification models, and evaluate their performance.
   - Use the trained models to predict the course category of recipes using the `predict_course_by_ingredients` function.

3. **Model Saving**:
   - The trained models, TF-IDF vectorizer, LabelEncoder, KMeans model, and cosine similarities matrix can be saved using the provided code snippets.

4. **Files for Recommendations**:
   - The recipes and their relevant data are stored in a CSV file named `recipes_for_recommendation.csv`.
   - The recipe titles for recommendation are stored in a text file named `recipe_titles.txt`.

## Files

- `recipe_recommendation.py`: Code for recipe recommendation using TF-IDF vectorization and KMeans clustering.
- `course_classification.py`: Code for course classification using various machine learning models.
- `tfidf_vectorizer.pkl`: Saved TF-IDF vectorizer model.
- `label_encoder.pkl`: Saved LabelEncoder model.
- `kmeans_model.pkl`: Saved KMeans clustering model.
- `cosine_similarities.pkl`: Saved cosine similarities matrix.
- `recipes_for_recommendation.csv`: CSV file containing recipe data for recommendations.
- `recipe_titles.txt`: Text file containing recipe titles for recommendations.
- `README.md`: This README file.

## Dependencies

The code relies on the following Python libraries and packages:

- pandas
- numpy
- nltk
- sklearn
- matplotlib
- seaborn
- wordcloud
- scattertext
- spacy
- plotly
- networkx
- cufflinks
- yellowbrick
- gensim
- joblib

Install these dependencies using the command provided in the [Installation](#installation) section.

