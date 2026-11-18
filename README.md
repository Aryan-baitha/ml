  # Adult Income Data Analysis (ml)

This repository contains an exploratory data analysis (EDA) of the Adult Income Dataset, downloaded from Kaggle (`wenruliu/adult-income-dataset`). 

## Overview
The project uses the `Employee.ipynb` Jupyter Notebook to load, visualize, and analyze demographic data (such as age, education, marital status, occupation, etc.) to understand income patterns (e.g., predicting whether income exceeds $50K/yr).

## Files in this Repository
- `Employee.ipynb`: The main notebook containing the data analysis code.
- `adult.csv`: The comma-separated values file containing the Adult Income dataset.

## Technologies Used
- **Python**
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **KaggleHub**: For fetching the dataset.

## How to Run
1. Install the required dependencies: `pip install pandas matplotlib seaborn kagglehub`
2. Open the Jupyter Notebook: `jupyter notebook Employee.ipynb`
3. Run the cells to reproduce the analysis. The notebook initially runs on Google Colab, and uses the `kagglehub` package to download the `adult.csv` dataset.
