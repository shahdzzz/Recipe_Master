
# Recipe Recommendation and Classification System

This repository contains code for a Recipe Recommendation and Classification System. The system uses Natural Language Processing (NLP) techniques to analyze and recommend recipes based on their ingredients. Additionally, it includes text classification models to predict the course category of a recipe (e.g., Main Course, Dessert, Starter, Snack, Beverage) based on its ingredients.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
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

