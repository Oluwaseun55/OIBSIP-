# Iris Flower Classification

## Overview
This project builds a machine learning model to classify iris flowers into one of three species — *Iris setosa*, *Iris versicolor*, and *Iris virginica* — based on four measurements: sepal length, sepal width, petal length, and petal width.

## Dataset
The classic Iris dataset (150 samples, 3 balanced classes, 4 numeric features).

## Approach
1. Explored the data with summary statistics and visualizations (box plots, pair plots) to understand how the features separate the three species.
2. Split the data into training and test sets.
3. Trained a classification model on the training set.
4. Evaluated performance on the test set using a confusion matrix and accuracy score.

## Results
- **Box Plot** — shows the spread of each feature across the three species. See `BoxPlot.png`.
- **Pair Plot** — shows how well the species separate across every pair of features. See `Pairplot.png`.
- **Confusion Matrix** — shows how many predictions were correct versus confused between species. See `ConfusionMatrix.png`.

## Files in this folder
- `IrisFlowerClassification.ipynb` — the full notebook: data loading, exploration, model training, and evaluation.
- `BoxPlot.png`, `Pairplot.png`, `ConfusionMatrix.png` — output visualizations referenced above.

## How to run
1. Open `IrisFlowerClassification.ipynb` in Jupyter Notebook.
2. Run all cells in order.

## Tools used
Python, Jupyter Notebook, pandas, scikit-learn, matplotlib/seaborn.
