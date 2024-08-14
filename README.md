# ⚽ Copa America 2024 Winner Prediction

Welcome to my project on predicting the winner of Copa America 2024 using machine learning! This project combines the excitement of soccer with the power of data science to simulate tournament outcomes and identify the potential winner. 🏆

## 📝 Table of Contents

- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Training & Evaluation](#model-training--evaluation)
- [Simulation & Prediction](#simulation--prediction)
- [Results](#results)
- [Technologies Used](#technologies-used)

## 📈 Project Overview

The goal of this project is to predict the winner of the Copa America 2024 tournament using a machine learning model. By scraping and analyzing match data, I was able to create a model that simulates match outcomes and predicts the overall winner based on several iterations.

## 📊 Data Collection

Data was scraped from fbref.com using `BeautifulSoup`. The data includes various metrics like goals, shots on target, free kicks, and more, which were used to build the predictive model.

## 🧹 Data Cleaning & Preprocessing

- Filled missing values using `pandas`.
- Encoded categorical variables such as Venue, Opponent, and Team.

## 🛠 Feature Engineering

Features were engineered to represent the performance of teams more effectively:
- **Attack Score**
- **Defense Score**
- **Goal Keeper Score**
- **Passing Score**

These features were used to build and refine the machine learning model.

## 🤖 Model Training & Evaluation

A `RandomForestClassifier` was used to predict match outcomes. The model was trained and evaluated using:

- **Accuracy Scores**
- **Confusion Matrices**
- **Classification Reports**

The model was then used to predict the probabilities of winning for each team in simulated matches.

## 🏅 Results

The project predicts that **Argentina** 🇦🇷 is the most likely winner of the Copa America 2024 tournament!

## 💻 Technologies Used

- **Python**: The core language used for the project.
- **pandas**: Data manipulation and cleaning.
- **BeautifulSoup**: Web scraping for data collection.
- **RandomForestClassifier**: Machine learning model used for predictions.
