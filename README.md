# IEEE PUA - Linear Regression Task

A beginner-friendly simple linear regression project for IEEE PUA AI & Machine Learning Track.

## Project files

- `Linear_Regression_IEEE.ipynb` - notebook (EDA, cleaning, training, evaluation, plots)
- `diabetes_regression.csv` - dataset used in the notebook
- `requirements.txt` - Python libraries needed to run it

## Dataset

The real-world Diabetes regression dataset included with **scikit-learn**, with 442 samples, 10 numerical features and a continuous target measuring disease progression. This project uses standardized `bmi` as the only input feature to demonstrate a simple fitted regression line. The dataset is included as CSV, so there is no need to download anything.

Source: scikit-learn built-in `load_diabetes` dataset (originally described by Efron et al., 2004). The dataset features are standardized as supplied by scikit-learn.

## How to run

1. Download or clone this project.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Linear_Regression_IEEE.ipynb` in Jupyter Notebook, VS Code, or Google Colab.
4. Run all cells in order. Keep the CSV next to the notebook.

## What the notebook covers

1. CSV loading with pandas
2. Checking missing values and duplicates, and numerical feature distributions
3. Scatter plots and feature correlations
4. An 80/20 train-test split
5. Linear Regression using scikit-learn
6. MSE, RMSE and MAE on the test set
7. Regression line, plus actual vs predicted values

This is for practice and education, not for clinical use.

## Submission

Upload these project files to a **public GitHub repository** and send the repository URL to the IEEE track lead.
