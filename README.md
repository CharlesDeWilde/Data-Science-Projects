# Data Science Projects

This repository contains several Jupyter notebooks exploring different data science techniques.

## Notebooks

- **2024 Pitching FIP ML.ipynb** – Builds regression models to predict Fielding Independent Pitching (FIP) for MLB pitchers using statistics loaded from an Excel file. Demonstrates data cleaning, correlation heatmaps with seaborn, and scikit-learn models (Linear Regression and Random Forest).
- **German Credit Data.ipynb** – Analyzes the German credit dataset to classify loan default risk. Applies preprocessing, decision tree classifiers, ensemble methods (Bagging, AdaBoost, Random Forest), and evaluates model performance.
- **Neural Network- Computer Components.ipynb** – Uses TensorFlow and Keras to create a neural network that predicts laptop retail prices from hardware specification data. Also shows train/test splitting and scikit-learn metrics.
- **Seaborn Visualizations.ipynb** – Showcases data visualization examples using seaborn’s built-in datasets (tips, iris, titanic) to demonstrate plots such as bar charts, box plots, and joint plots.

## Environment

Notebooks were created with **Python 3.10.9**. They rely on the following key packages:

- `pandas`
- `seaborn`
- `scikit-learn`
- `tensorflow` (used in the neural network notebook)

Install them using `pip install pandas seaborn scikit-learn tensorflow` if needed.

## Datasets

Datasets referenced by the notebooks are not included in the repository:

- `pitcher_stats.xlsx` – Excel file of MLB pitcher statistics used by *2024 Pitching FIP ML.ipynb*.
- `credit.csv` – German credit dataset used by *German Credit Data.ipynb* (available from Kaggle or UCI Machine Learning Repository).
- `LaptopSales.csv` – Laptop sales data used by *Neural Network- Computer Components.ipynb*.
- Seaborn demo notebook downloads `tips`, `iris`, and `titanic` automatically via `sns.load_dataset`.

Download or prepare these datasets separately and place them in the paths expected by the notebooks (or adjust the file paths within the notebooks).

## Running the notebooks

1. Install the required packages and ensure Python 3.10 is available.
2. Acquire the datasets above and put them in this repository directory (or modify the file paths in the notebooks).
3. Launch Jupyter and open any notebook:
   ```bash
   jupyter notebook
   ```
4. Execute the cells in order to reproduce the analyses and models.
