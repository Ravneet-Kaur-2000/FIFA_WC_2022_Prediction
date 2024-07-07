
<p align="center">

  <h2 align="center">Football Match Prediction using Exploratory Data Analysis & Multi-Output Regression</h2>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <li><a href="#paper-link">Paper Link</a></li>
    <li><a href="#abstract">Abstract</a></li>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#dataset">Dataset</a></li>
      <li><a href="#models">Models</a></li>
      <li><a href="#results">Results</a></li>
</details>


## Paper Link
Paper: [Link](https://link.springer.com/chapter/10.1007/978-3-031-24848-1_15)

## Abstract
Football is one of the world’s most popular and
highly spectated games. The unpredictability of a football
match is what makes this sport special and loved. Crowd
influences, home team advantage, hostile away game
atmosphere, the underdog wins, and comebacks make it such
a hard game to predict. This project helps in predicting the outcome of a football match and thus,
in turn, predicting the winners of 2022 FIFA
World Cup using Exploratory Data Analysis (EDA) to
determine the important features of the dataset and then
training various machine learning techniques to predict the
score. The algorithms tested are Random Forests, Decision
Trees, K-Nearest Neighbors, XGBoost, and Gradient
Boosting. In the context of international football matches, the
findings of this comparative analysis revealed that the
XGBoost and Gradient Booster produced the highest average
accuracy of 98.34%.


## Introduction
Multiple techniques, including feature similarity techniques,
ensemble learning techniques, as well as tree-boosting
methods, have been utilised to obtain the highest possible
accuracy in predicting football games based on previous
results. All these algorithms have been wrapped by the parent
Multi-output regressor, whose goal is to discover a mapping
from an input feature space to an output space with multiple
variables

## Dataset
The dataset contained 43,421 international football match results dating from the first officially recorded international match in 1872 to 2022. The matches ranged from FIFA World Cup matches and playoffs to friendly matches, as well as Continental Cups such as the Euros, Africa Cup of Nations, and Copa America.

## Models
We evaluated the following machine learning models for Football Match Prediction:
1. Random Forest
2. Decison Trees
3. K Nearest Neighbors
4. XGBoost
5. Gradient Boosting

## Results
The tree-boosting algorithms, such as Gradient Boosting and XGBoost, return higher R² scores as well as lower RMSE scores, indicating a superior fit to the training data. However, XGBoost returns results exponentially faster than Gradient Boosting due to its ability to efficiently prune the trees. The XGBoost model was further used to predict the results of the FIFA World Cup 2022, predicting Argentina as the winner
