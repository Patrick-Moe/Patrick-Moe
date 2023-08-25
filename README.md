# Summoner Win Prediction

This data science project involves utilizing the Riot Games API to obtain summoner and match data in order to predict match outcomes. The primary focus is on analyzing the features that contribute significantly to a summoner's win or loss. The project encompasses the complete data science pipeline, from data collection to model evaluation.

## Features

The project leverages the Riot Games API through an API key for data retrieval. Key features include:
- Data collection via multiple API calls to acquire essential information.
- Exploratory Data Analysis (EDA) utilizing Matplotlib for data visualization.
- Applying machine learning models, including K-Nearest Neighbors, Decision Trees, and Random Forests, to predict match outcomes.
- Evaluation using classification reports to assess model performance.

## Getting Started

### Prerequisites

Before running the project, ensure you have:
- Python (version X.X)
- Necessary libraries (pandas, matplotlib, scikit-learn, etc.)

### Installation

1. Clone this repository to your local machine.

3. Obtain a Riot API key by signing up on the Riot Games developer portal.

## Usage

The project aims to understand the factors influencing summoner match outcomes by utilizing Riot Games API data. Key steps include:
- Data collection via Riot API, involving multiple API calls.
- Exploratory Data Analysis, including the creation of visualizations for better understanding.
- Model training using various classifiers and evaluation through classification reports.

## Data

The project gathers data from the Riot API to perform analysis on summoner attributes and match statistics.

## Exploratory Data Analysis

EDA is conducted using Matplotlib graphs, aiding in insights and patterns discovery within the dataset.

## Modeling

Multiple machine learning classifiers are employed, including K-Nearest Neighbors, Decision Trees, and Random Forests. Note that models claiming 100% accuracy may indicate potential overfitting.

## Evaluation

Model performance is evaluated using classification reports. An example for the Decision Tree model:
```plaintext
           precision    recall  f1-score   support

        0       0.69      0.64      0.67        14
        1       0.64      0.69      0.67        13

 accuracy                           0.67        27
macro avg       0.67      0.67      0.67        27
weighted avg       0.67      0.67      0.67        27

## Results
The Random Forest model yielded the best classification results with 100% accuracy:
              precision    recall  f1-score   support

           0       0.87      0.93      0.90        14
           1       0.92      0.85      0.88        13

    accuracy                           0.89        27
   macro avg       0.89      0.89      0.89        27
weighted avg       0.89      0.89      0.89        27

## Future Changes

If provided with additional access to Riot API data, future improvements might include segmenting results by specific roles in League of Legends, allowing for more detailed evaluations of each role's impact on match outcomes. Additionally, expanding the analysis to include champion-specific data could provide further insights.
